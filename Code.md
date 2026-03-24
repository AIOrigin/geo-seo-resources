# Code Guide

This repository is primarily a docs and skills repository, not a product application repository.

## Primary Structure

- `docs/` for durable reference material and repository-level documentation
- `examples/` for example artifacts
- `reports/` for public-safe report samples
- `.cursor/skills/` for canonical skills
- `codex/skills/` and `.claude/skills/` for platform adapters
- `assets/branding/` for repository icon and branding assets

## Naming Rules

- Prefer generic capability names over project-bound names
- Use kebab-case for skill directory names
- Keep the same generic skill ID across:
  - `.cursor/skills/`
  - `codex/skills/`
  - `.claude/skills/`
- Treat legacy workspace-specific names as source references only

## Skill Rules

- `.cursor/skills/` is the canonical layer
- Every canonical skill must have a matching adapter in:
  - `codex/skills/`
  - `.claude/skills/`
- Keep adapter files thin and point them back to the canonical skill body
- Update `docs/skills-index.md` and `docs/skill-route-inventory.md` when adding or renaming skills

## Documentation Rules

- Keep README navigation synchronized across all language variants
- Add new durable docs under `docs/`
- Use simple, stable file names
- Prefer concise, execution-focused writing

## Quality Rules

- Markdown should pass lint checks
- Public links should pass link checks where possible
- JSON samples should remain valid
- Do not add private credentials, tokens, or secret URLs

## Change Checklist

When changing this repository:

1. Update canonical skill files first
2. Sync Codex and Claude Code adapters
3. Refresh the skill index and mapping docs
4. Refresh README language navigation if needed
5. Run the repository quality checks
