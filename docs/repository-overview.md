# Repository Overview

`geo-seo-resources` is a reusable SEO and GEO skills repository plus a public-safe reference-docs repository.

## What This Repository Contains

This repository combines two layers:

1. Public-safe reference material
2. Generic AI skill definitions for SEO and GEO work

## Main Paths

| Path | Purpose |
| --- | --- |
| `README.md` | English entry point |
| `README.zh-CN.md` | Simplified Chinese entry point |
| `README.zh-Hant.md` | Traditional Chinese entry point |
| `README.ja.md` | Japanese entry point |
| `docs/` | Reference docs, skill docs, branding, CI notes |
| `examples/` | Example route maps and supporting examples |
| `reports/` | Public-safe GEO report samples |
| `.cursor/skills/` | Canonical generic skills |
| `codex/skills/` | Codex adapter skills |
| `.claude/skills/` | Claude Code adapter skills |
| `assets/branding/` | Repository icon and branding assets |
| `.github/workflows/` | Docs-focused CI workflow |

## Implemented Skill Library

The repository currently includes `17` implemented generic skills across three platforms.

### Discovery and analysis

- `browser-discovery-seo-workflow`
- `site-structure-seo-analyzer`
- `reference-site-analysis`

### SEO execution workflows

- `landing-capability-pages`
- `site-seo-verify-generate`
- `seo-growth-workflow`
- `seo-tracking-system`

### Route clusters

- `capability-route-cluster`
- `guide-cluster-getting-started`
- `guide-cluster-prompts-workflow`
- `guide-cluster-troubleshooting-reference`
- `guide-cluster-comparisons-decision`
- `prompt-template-cluster-core-formulas`
- `prompt-template-cluster-optimization-methods`

### Asset and content workflows

- `og-preview-generator`
- `referral-traffic-analysis`
- `video-to-story-workflow`

## Current Documentation Set

Core docs already present:

- `docs/skills-index.md`
- `docs/skill-route-inventory.md`
- `docs/llms-txt-guide.md`
- `docs/schema-examples.md`
- `docs/citability-checklist.md`
- `docs/reference-site-examples.md`
- `docs/report-samples.md`
- `docs/measurement-plan.md`

Core docs added in this preparation pass:

- `docs/repository-overview.md`
- `docs/ci-and-quality.md`
- `Code.md`
- `agent.md`

## Repository Identity

This repository should now be treated as:

- a reusable SEO and GEO skills library
- a public-safe documentation layer
- a generic toolkit, not a mirror of any one vendor’s private workspace

Canonical skill names and branding stay generic; illustrative URLs use reserved documentation domains where noted.

## Recommended Next Actions

1. Connect the repository to its final GitHub remote so live CI badges can replace local badge SVGs.
2. Decide whether to keep the current SVG branding as-is or add a higher-fidelity social-preview raster.
3. Optionally add contribution and changelog documents if external collaboration is expected.
