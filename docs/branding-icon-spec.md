# Branding And Icon Spec

This repository uses a generic SEO and GEO identity.

## Branding Goal

The visual system should communicate:

- discoverability
- structure
- route mapping
- AI-readable organization
- reusable technical workflows

It should not look like:

- an official third-party product logo you do not own
- a video-generation consumer app icon
- a playful mascot brand

## Core Icon Concept

Recommended icon concept:

- Base shape: rounded square
- Main motif: connected route graph with three nodes
- Secondary motif: discovery arc or search signal ring
- Reading: structured routes + discoverability + technical workflow

## Visual Style

- Flat vector style
- Clean geometry
- Strong contrast
- Minimal internal detail
- Works at small sizes such as GitHub avatars and badges

Avoid:

- glossy gradients
- mascots
- 3D rendering
- product-app style sparkle effects
- entertainment-first visual language

## Color Palette

### Primary

- `#173B6D` deep navy
- role: structure, trust, repository backbone

### Secondary

- `#1AA3A8` teal
- role: discovery, GEO signal, AI-readable flow

### Accent

- `#F7FAFC` near-white
- role: contrast, linework, readability

### Optional dark neutral

- `#0F172A`
- role: text, badge border, dark-theme support

## Icon Construction Rules

1. Keep the silhouette simple.
2. Use one main route path and 2 to 3 visible nodes.
3. Keep enough whitespace around the mark.
4. Make sure the icon still reads clearly at 32x32.
5. Prefer SVG as the canonical source.

## Asset Set

Recommended repository branding assets:

- `assets/branding/icon.svg`
- `assets/branding/social-preview.svg`
- `assets/branding/README.md`

Optional later:

- `assets/branding/icon-512.png`
- `assets/branding/social-preview.png`
- `assets/branding/favicon.ico`

## Badge Rules

Badge styling should stay neutral and technical.

Preferred badges:

- CI
- Markdown quality
- Link check
- JSON validation

Badge labels should describe checks, not marketing claims.

## Usage Rules

- Use the generic icon for repository-level branding only.
- Do not present the icon as an official third-party brand mark you do not own.
- Keep docs, README, and social-preview assets visually aligned to the same palette.

## Current Implementation Direction

The current repository icon asset should use:

- deep navy background
- teal route lines and nodes
- near-white highlight ring

This keeps the repository aligned with generic SEO/GEO infrastructure rather than any one project source.
