# Skills Index

This repository stores a reusable SEO and GEO skill library with one canonical layer and two platform adapter layers:

- Cursor: `.cursor/skills/`
- Codex: `codex/skills/`
- Claude Code: `.claude/skills/`

## Coverage Summary

- Implemented canonical skills: `17`
- Cursor skill files: `17`
- Codex skill adapters: `17`
- Claude Code skill adapters: `17`

## Where Definitions Live In This Repository

- Skill index and families: `.cursor/skills/agent-skills-index.md`
- Upstream name mapping and route slug inventory: `docs/skill-route-inventory.md`
- Public URL examples: `docs/reference-site-examples.md`. Path-only IA map: `examples/reference-route-map.md` (no referral/README integration in that file).

Private SEO workspaces or app source trees are not vendored here; docs only reference this repo and public sites.

## Implemented Skill Families

| Family | Implemented skills | Notes |
| --- | ---: | --- |
| Discovery and analysis | 3 | Search evidence, site analysis, and reference-site comparison |
| SEO execution workflows | 4 | Page creation, verify-to-generate flow, growth workflow, and tracking |
| Route clusters | 7 | Capability, guide, and prompt-template cluster skills |
| Asset and content workflows | 3 | OG previews, referral analysis, and video-to-story transformation |

## Implemented Canonical Skills

| Generic skill ID | Family | Status | Cursor | Codex | Claude Code |
| --- | --- | --- | --- | --- | --- |
| `browser-discovery-seo-workflow` | Discovery and analysis | Implemented | `.cursor/skills/browser-discovery-seo-workflow/SKILL.md` | `codex/skills/browser-discovery-seo-workflow/SKILL.md` | `.claude/skills/browser-discovery-seo-workflow/SKILL.md` |
| `site-structure-seo-analyzer` | Discovery and analysis | Implemented | `.cursor/skills/site-structure-seo-analyzer/SKILL.md` | `codex/skills/site-structure-seo-analyzer/SKILL.md` | `.claude/skills/site-structure-seo-analyzer/SKILL.md` |
| `reference-site-analysis` | Discovery and analysis | Implemented | `.cursor/skills/reference-site-analysis/SKILL.md` | `codex/skills/reference-site-analysis/SKILL.md` | `.claude/skills/reference-site-analysis/SKILL.md` |
| `landing-capability-pages` | SEO execution workflows | Implemented | `.cursor/skills/landing-capability-pages/SKILL.md` | `codex/skills/landing-capability-pages/SKILL.md` | `.claude/skills/landing-capability-pages/SKILL.md` |
| `site-seo-verify-generate` | SEO execution workflows | Implemented | `.cursor/skills/site-seo-verify-generate/SKILL.md` | `codex/skills/site-seo-verify-generate/SKILL.md` | `.claude/skills/site-seo-verify-generate/SKILL.md` |
| `seo-growth-workflow` | SEO execution workflows | Implemented | `.cursor/skills/seo-growth-workflow/SKILL.md` | `codex/skills/seo-growth-workflow/SKILL.md` | `.claude/skills/seo-growth-workflow/SKILL.md` |
| `seo-tracking-system` | SEO execution workflows | Implemented | `.cursor/skills/seo-tracking-system/SKILL.md` | `codex/skills/seo-tracking-system/SKILL.md` | `.claude/skills/seo-tracking-system/SKILL.md` |
| `capability-route-cluster` | Route clusters | Implemented | `.cursor/skills/capability-route-cluster/SKILL.md` | `codex/skills/capability-route-cluster/SKILL.md` | `.claude/skills/capability-route-cluster/SKILL.md` |
| `guide-cluster-getting-started` | Route clusters | Implemented | `.cursor/skills/guide-cluster-getting-started/SKILL.md` | `codex/skills/guide-cluster-getting-started/SKILL.md` | `.claude/skills/guide-cluster-getting-started/SKILL.md` |
| `guide-cluster-prompts-workflow` | Route clusters | Implemented | `.cursor/skills/guide-cluster-prompts-workflow/SKILL.md` | `codex/skills/guide-cluster-prompts-workflow/SKILL.md` | `.claude/skills/guide-cluster-prompts-workflow/SKILL.md` |
| `guide-cluster-troubleshooting-reference` | Route clusters | Implemented | `.cursor/skills/guide-cluster-troubleshooting-reference/SKILL.md` | `codex/skills/guide-cluster-troubleshooting-reference/SKILL.md` | `.claude/skills/guide-cluster-troubleshooting-reference/SKILL.md` |
| `guide-cluster-comparisons-decision` | Route clusters | Implemented | `.cursor/skills/guide-cluster-comparisons-decision/SKILL.md` | `codex/skills/guide-cluster-comparisons-decision/SKILL.md` | `.claude/skills/guide-cluster-comparisons-decision/SKILL.md` |
| `prompt-template-cluster-core-formulas` | Route clusters | Implemented | `.cursor/skills/prompt-template-cluster-core-formulas/SKILL.md` | `codex/skills/prompt-template-cluster-core-formulas/SKILL.md` | `.claude/skills/prompt-template-cluster-core-formulas/SKILL.md` |
| `prompt-template-cluster-optimization-methods` | Route clusters | Implemented | `.cursor/skills/prompt-template-cluster-optimization-methods/SKILL.md` | `codex/skills/prompt-template-cluster-optimization-methods/SKILL.md` | `.claude/skills/prompt-template-cluster-optimization-methods/SKILL.md` |
| `og-preview-generator` | Asset and content workflows | Implemented | `.cursor/skills/og-preview-generator/SKILL.md` | `codex/skills/og-preview-generator/SKILL.md` | `.claude/skills/og-preview-generator/SKILL.md` |
| `referral-traffic-analysis` | Asset and content workflows | Implemented | `.cursor/skills/referral-traffic-analysis/SKILL.md` | `codex/skills/referral-traffic-analysis/SKILL.md` | `.claude/skills/referral-traffic-analysis/SKILL.md` |
| `video-to-story-workflow` | Asset and content workflows | Implemented | `.cursor/skills/video-to-story-workflow/SKILL.md` | `codex/skills/video-to-story-workflow/SKILL.md` | `.claude/skills/video-to-story-workflow/SKILL.md` |

## Repository Layout

```text
.cursor/
  skills/
    agent-skills-index.md
    <generic canonical skill>/SKILL.md
codex/
  skills/
    <generic adapter>/SKILL.md
.claude/
  skills/
    <generic adapter>/SKILL.md
docs/
  skills-index.md
  skill-route-inventory.md
```

## Notes

- `.cursor/skills/` is the canonical layer inside this repository.
- `codex/skills/` and `.claude/skills/` are adapter layers with the same generic IDs.
- Legacy workspace-specific names are treated as upstream examples or source references, not canonical skill names for this repo.
