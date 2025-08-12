# YOR Construction Schema Files

## Structure
- `/organization` - Company-wide schema markup
- `/locations/[city]` - Location-specific markup
- `/llm-data` - Machine-readable business data

## Usage (Working Links)
```html
<!-- Organization Schema -->
<script type="application/ld+json" 
        src="https://raw.githubusercontent.com/DFYRANKINGS/YOR-Construction-Schema-Markup/main/organization/global-schema.json">
</script>

<!-- Valley Village Location -->
<script type="application/ld+json" 
        src="https://raw.githubusercontent.com/DFYRANKINGS/YOR-Construction-Schema-Markup/main/locations/valley-village/schema.json">
</script>
