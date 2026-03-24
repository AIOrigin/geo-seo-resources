# Skill And Route Inventory

This document maps legacy or private-workspace skill identifiers to the **generic canonical** names used in this repository. Example URL paths and slugs are **illustrative**; replace them with your own live site.

Historical upstream skill files lived in a separate private SEO workspace and are **not** copied into this repository. Use the **in-repo canonical** column below for real paths.

## Upstream Name To Generic Canonical Name

| Upstream or old mirror name | Generic canonical name | Source type | In-repo canonical skill |
| --- | --- | --- | --- |
| `browser-seo-workflow` | `browser-discovery-seo-workflow` | SEO workspace skill | `.cursor/skills/browser-discovery-seo-workflow/SKILL.md` |
| `website-style-seo-analyzer` | `site-structure-seo-analyzer` | SEO workspace skill | `.cursor/skills/site-structure-seo-analyzer/SKILL.md` |
| `workspace-capability-pages` | `landing-capability-pages` | SEO workspace skill | `.cursor/skills/landing-capability-pages/SKILL.md` |
| `workspace-seo-verify-generate` | `site-seo-verify-generate` | SEO workspace workflow | `.cursor/skills/site-seo-verify-generate/SKILL.md` |
| `workspace-capabilities` | `capability-route-cluster` | Route-derived cluster | `.cursor/skills/capability-route-cluster/SKILL.md` |
| `workspace-guides-getting-started` | `guide-cluster-getting-started` | Route-derived cluster | `.cursor/skills/guide-cluster-getting-started/SKILL.md` |
| `workspace-guides-prompts-workflow` | `guide-cluster-prompts-workflow` | Route-derived cluster | `.cursor/skills/guide-cluster-prompts-workflow/SKILL.md` |
| `workspace-guides-troubleshooting-reference` | `guide-cluster-troubleshooting-reference` | Route-derived cluster | `.cursor/skills/guide-cluster-troubleshooting-reference/SKILL.md` |
| `workspace-guides-comparisons-decision` | `guide-cluster-comparisons-decision` | Route-derived cluster | `.cursor/skills/guide-cluster-comparisons-decision/SKILL.md` |
| `workspace-prompt-templates-core-formulas` | `prompt-template-cluster-core-formulas` | Route-derived cluster | `.cursor/skills/prompt-template-cluster-core-formulas/SKILL.md` |
| `workspace-prompt-templates-optimization-methods` | `prompt-template-cluster-optimization-methods` | Route-derived cluster | `.cursor/skills/prompt-template-cluster-optimization-methods/SKILL.md` |
| `tracking-system` | `seo-tracking-system` | SEO workspace workflow | `.cursor/skills/seo-tracking-system/SKILL.md` |
| `og-preview-capture` | `og-preview-generator` | SEO workspace skill | `.cursor/skills/og-preview-generator/SKILL.md` |
| `referral-traffic-learning` | `referral-traffic-analysis` | SEO workspace skill | `.cursor/skills/referral-traffic-analysis/SKILL.md` |
| `growth-system-booster` | `seo-growth-workflow` | SEO workspace skill | `.cursor/skills/seo-growth-workflow/SKILL.md` |
| `video-to-story-workflow` | `video-to-story-workflow` | SEO workspace skill | `.cursor/skills/video-to-story-workflow/SKILL.md` |
| `reference-site-clone-learning` | `reference-site-analysis` | SEO workspace skill | `.cursor/skills/reference-site-analysis/SKILL.md` |

## Generic Clusters And Example Route Groups

| Generic canonical name | Example route group (illustrative) | Covered items |
| --- | --- | --- |
| `capability-route-cluster` | Capabilities | 10 capability slugs |
| `guide-cluster-getting-started` | Getting started guides | 3 guide slugs |
| `guide-cluster-prompts-workflow` | Prompts and workflow guides | 7 guide slugs |
| `guide-cluster-troubleshooting-reference` | Troubleshooting and reference guides | 4 guide slugs |
| `guide-cluster-comparisons-decision` | Comparisons and decision guides | 4 guide slugs |
| `prompt-template-cluster-core-formulas` | Core formulas | 2 prompt-template slugs |
| `prompt-template-cluster-optimization-methods` | Optimization methods | 2 prompt-template slugs |

## Capability Coverage

Inventory reference: path-level IA only in `examples/reference-route-map.md`—no bundled referral or README coupling (app source trees are not vendored here).

- `consistency`
- `camera-motion`
- `creative-template`
- `story-completion`
- `video-extension`
- `native-audio`
- `one-shot`
- `video-editing`
- `music-sync`
- `emotion-expression`

## Guide Group Coverage

Inventory reference: `docs/reference-site-examples.md`.

### `guide-cluster-getting-started`

- `product-overview`
- `getting-started`
- `pricing-and-access`

### `guide-cluster-prompts-workflow`

- `tutorial`
- `prompts`
- `prompt-library`
- `image-to-video`
- `multimodal`
- `api-guide`
- `best-practices`

### `guide-cluster-troubleshooting-reference`

- `faq`
- `glossary`
- `troubleshooting`
- `technical-architecture`

### `guide-cluster-comparisons-decision`

- `compare`
- `use-cases`
- `vs-competitor-a`
- `vs-competitor-b`

## Prompt Template Coverage

Inventory reference: `docs/reference-site-examples.md`.

### `prompt-template-cluster-core-formulas`

- `character-video`
- `scene-landscape-video`

### `prompt-template-cluster-optimization-methods`

- `advanced-prompt-tips`
- `display-and-synthesis`

## Platform Mapping Rule

Each generic canonical skill is represented three times:

1. Canonical skill in `.cursor/skills/<skill>/SKILL.md`
2. Codex adapter in `codex/skills/<skill>/SKILL.md`
3. Claude Code adapter in `.claude/skills/<skill>/SKILL.md`

The adapter files stay short and point back to the canonical Cursor-formatted skill body to avoid drift.
