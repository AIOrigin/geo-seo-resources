# CI And Quality

This repository uses a **lightweight docs-focused check** on GitHub (Markdown lint, targeted link check, JSON sample validation). It is **not** a product CI/CD or deployment pipeline; see the README section *Lightweight quality checks* for how this is framed for readers.

## CI Scope

The CI workflow lives at `.github/workflows/ci.yml` and checks:

1. Markdown lint
2. Public link validity
3. JSON sample validity

## What Gets Checked

- `README*.md`
- `docs/**/*.md`
- `examples/**/*.md`
- `reports/**/*.md`
- `Code.md`
- `agent.md`
- all `SKILL.md` files through the Markdown lint step

## Local Validation

Run these commands from the repository root:

```bash
npx markdownlint-cli2 "**/*.md"
python3 -m json.tool reports/reference-geo-audit-sample.json > /dev/null
```

Optional link check if `lychee` is installed:

```bash
lychee --config .github/lychee.toml "./README*.md" "./docs/**/*.md" "./examples/**/*.md" "./reports/**/*.md" "./Code.md" "./agent.md"
```

## Badge Strategy

Because this repository does not currently have a configured GitHub remote in local checkout, live GitHub Actions badge URLs cannot be generated automatically from the repository itself.

Current approach:

- Use local status badges in `assets/branding/badges/` to show that CI and local checks are prepared
- Replace them with live GitHub Actions badge URLs after the final remote path is known

## Recommended Live Badge URLs

After GitHub remote setup, replace the local badge image paths with:

```text
https://github.com/<owner>/<repo>/actions/workflows/ci.yml/badge.svg
```

and link them to:

```text
https://github.com/<owner>/<repo>/actions/workflows/ci.yml
```
