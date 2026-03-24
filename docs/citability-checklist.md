# Citability Checklist

This checklist is derived from the current GEO tooling and the public sample outputs in this repository.

## What Citability Means Here

Citability is a practical heuristic for whether a content block is easy for AI systems to extract, quote, and route.

Higher-citability passages usually have:

- a clear answer early in the paragraph
- self-contained wording
- stable structure
- enough specificity to be useful
- a moderate, readable length

## Checklist

- Start the section with a direct answer, not only framing text.
- Use question-led headings where that improves retrieval.
- Keep one idea per block.
- Reduce vague pronouns that require too much prior context.
- Add factual anchors such as dates, counts, ranges, supported inputs, or named sources where appropriate.
- Prefer clean sentence structure over decorative wording.
- Separate navigation text from answer text.
- Avoid mixing too many unrelated ideas into the same section.
- Turn important prompt or workflow advice into quotable blocks rather than buried prose.

## Current Public Sample Signals

From the illustrative audit sample in this repo:

- guide overview citability: `40.6 / 100`
- prompt-template citability: `34.0 / 100`

This means the illustrated pages are readable and useful, but still have room to become more extractable for AI answer systems.

## Example Pages To Improve First

- [Product overview guide](https://www.example.org/guides/product-overview?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Advanced prompt techniques](https://www.example.org/prompt-templates/advanced-prompt-tips?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Prompt templates hub](https://www.example.org/prompt-templates?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)

## Easy Wins

- convert intro blocks into direct-answer blocks
- add one stronger statistic or factual anchor where available
- isolate FAQ-style answers from surrounding navigation text
- publish more complete Input/Output examples for prompt-template pages
