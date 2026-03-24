# Schema Examples

This repository does not present generic schema templates as production-ready copy-paste assets.

Instead, it uses a **reference documentation site pattern** as a reminder that schema should be mapped to:

- real route types
- real ownership and boundary statements
- real content fields
- real update and source behavior

## Useful Schema Families

For a GEO-aware content site, these are usually the most useful schema families:

- `WebSite`
- `Organization`
- `WebPage`
- `Article`
- `FAQPage`
- `HowTo`
- `CollectionPage`
- `ItemList`
- `SoftwareApplication`

## Example Areas

On a typical reference documentation site, schema is especially relevant for:

- homepage and site entity framing
- guide detail pages
- prompt-template hub/detail pages
- FAQ sections
- structured collection pages

## Important Constraint

If a site is operating as a third-party explanation site, schema must not imply:

- official ownership of the underlying product
- authorization or partnership that does not exist
- stronger brand affiliation than what is documented

## Suggested Mapping Workflow

1. Start with route type.
2. Decide the correct schema family for that route.
3. Map only real content fields.
4. Add legal or boundary pages where needed.
5. Verify the schema against rendered output, not just source templates.

## Related Illustrative Pages

- [Homepage](https://www.example.org/?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Guides hub](https://www.example.org/guides?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
- [Prompt templates hub](https://www.example.org/prompt-templates?utm_source=github&utm_medium=referral&utm_campaign=geo_seo_resources)
