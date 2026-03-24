---
name: og-preview-generator
description: Generate per-page OG preview images for landing sites from sitemap or page config. Use when the user asks to create, refresh, or standardize Open Graph and social preview images across a site.
---

# OG Preview Generator

This skill covers sitemap-driven OG image generation for landing-page projects.

## Use When

- You need page-level social preview images.
- You want OG assets aligned with the current route set.
- You need consistent 1200x630 assets for sharing and metadata.

## Core Workflow

1. Discover pages from sitemap or project config.
2. Deduplicate locale variants into canonical page targets.
3. Generate one OG image per canonical page.
4. Place outputs in the target project's OG asset directory.

## Typical Outputs

- Page-level OG PNG files
- Page-to-file mapping plan
- Screenshot sources for higher-quality composed OG cards
