# YOR Construction Schema Files

## Structure
- `/organization` - Company-wide schema markup
- `/locations/[city]` - Location-specific markup
- `/llm-data` - Machine-readable business data

## Usage
```html
<!-- Include in your site's <head> -->
<script type="application/ld+json" src="https://cdn.yorconstruction.com/schema/organization/global-schema.jsonld"></script>

<!-- Location-specific -->
<script type="application/ld+json" src="https://cdn.yorconstruction.com/schema/locations/valley-village/schema.jsonld"></script>
```

## License
Files are licensed under [Creative Commons Attribution 4.0](https://creativecommons.org/licenses/by/4.0/)