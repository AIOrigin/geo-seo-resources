# Agent Skills Index

This index lists the generic canonical skill set stored in this repository.

## Canonical Rule

- `.cursor/skills/` is the canonical skill layer in this repository.
- `codex/skills/` and `.claude/skills/` mirror the same generic skill IDs as thin adapters.
- Legacy workspace names and illustrative route slugs are documented in `docs/skill-route-inventory.md`.

## Implemented Skills

| Skill | Family | Notes |
| --- | --- | --- |
| `browser-discovery-seo-workflow` | Discovery and analysis | Generic mirror of an upstream SEO workspace skill name |
| `site-structure-seo-analyzer` | Discovery and analysis | Generic mirror of an upstream SEO workspace skill name |
| `reference-site-analysis` | Discovery and analysis | Generic mirror of an upstream SEO workspace skill name |
| `landing-capability-pages` | SEO execution workflows | Generic mirror of an upstream SEO workspace skill name |
| `site-seo-verify-generate` | SEO execution workflows | Generic mirror of an upstream SEO workspace workflow name |
| `seo-growth-workflow` | SEO execution workflows | Generic mirror of an upstream SEO workspace skill name |
| `seo-tracking-system` | SEO execution workflows | Generic mirror of an upstream SEO workspace workflow name |
| `capability-route-cluster` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `guide-cluster-getting-started` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `guide-cluster-prompts-workflow` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `guide-cluster-troubleshooting-reference` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `guide-cluster-comparisons-decision` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `prompt-template-cluster-core-formulas` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `prompt-template-cluster-optimization-methods` | Route clusters | Slug inventory in `docs/skill-route-inventory.md` |
| `og-preview-generator` | Asset and content workflows | Generic mirror of an upstream SEO workspace skill name |
| `referral-traffic-analysis` | Asset and content workflows | Generic mirror of an upstream SEO workspace skill name |
| `video-to-story-workflow` | Asset and content workflows | Same ID as upstream; canonical copy lives in this repo |

## Reading Order

1. Read the target `SKILL.md` in `.cursor/skills/<skill>/`
2. Read `docs/skill-route-inventory.md` when you need upstream source mapping
3. Read `docs/skills-index.md` for platform coverage and implementation status
