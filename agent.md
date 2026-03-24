# Agent Guide

This file explains how AI agents should use and maintain this repository.

## What This Repository Is

This repository is a reusable SEO and GEO skills library plus a public-safe documentation layer.

It is not:

- an official repository for any specific vendor product
- a product application repository
- a deployment target for a web app

## Canonical Skill Rule

- `.cursor/skills/` is the canonical skill layer
- `codex/skills/` mirrors the same generic skill IDs for Codex
- `.claude/skills/` mirrors the same generic skill IDs for Claude Code

When updating a skill:

1. Update the canonical `.cursor/skills/<skill>/SKILL.md`
2. Sync the matching Codex adapter
3. Sync the matching Claude Code adapter
4. Update:
   - `docs/skills-index.md`
   - `docs/skill-route-inventory.md`
   - `.cursor/skills/agent-skills-index.md`

## Naming Rule

- Canonical names should describe reusable capability
- Do not use project-bound names as canonical names
- Vendor- or site-specific terms belong only in your fork’s private notes unless you intentionally publish them.

## Document Rules

- English README is the default entry point
- Keep the language switcher aligned across:
  - `README.md`
  - `README.zh-CN.md`
  - `README.zh-Hant.md`
  - `README.ja.md`
- Put repository-wide docs under `docs/`

## Branding Rule

- The repository branding should stay generic SEO/GEO
- Do not make the icon look like an official third-party product logo you do not own
- Keep icon and social-preview assets under `assets/branding/`

## Quality Rule

Before considering a change complete:

1. Markdown should lint cleanly
2. Public links should be checked
3. JSON samples should validate
4. Documentation and skill indices should stay in sync

## Fast Reading Order For Agents

1. `README.md`
2. `docs/repository-overview.md`
3. `docs/skills-index.md`
4. `docs/skill-route-inventory.md`
5. `.cursor/skills/agent-skills-index.md`
