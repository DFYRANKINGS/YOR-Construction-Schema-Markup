# YOR Construction Schema Files

## Structure
- `/organization` - Company-wide schema markup
- `/locations/[city]` - Location-specific markup (e.g., `Valley-Village`, `Van-Nuys`)
- `/llm-data` - Machine-readable business data

## Usage
```html
<!-- Organization Schema -->
<script type="application/ld+json" src="https://DFYRANKINGS.github.io/YOR-Construction-Schema-Markup/organization/global-schema.json"></script>

<!-- Valley Village Location -->
<script type="application/ld+json" src="https://DFYRANKINGS.github.io/YOR-Construction-Schema-Markup/locations/Valley-Village/schema.json"></script>
