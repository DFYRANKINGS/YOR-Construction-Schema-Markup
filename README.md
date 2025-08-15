# YOR Construction Schema Files

## Structure
- `/YOR-Construction-Schema.json` - Primary company schema
- `/locations/[city]/` - Location-specific schemas (e.g., `valley-village/schema.json`)
- `/llm-data/` - Machine-readable business data

## Usage
```html
<!-- Main Company Schema -->
<script type="application/ld+json" 
        src="https://raw.githubusercontent.com/DFYRANKINGS/YOR-Construction-Schema-Markup/main/YOR-Construction-Schema.json">
</script>

<!-- Valley Village Location -->
<script type="application/ld+json" 
        src="https://raw.githubusercontent.com/DFYRANKINGS/YOR-Construction-Schema-Markup/main/locations/valley-village/schema.json">
</script>

<!-- Van Nuys Location -->
<script type="application/ld+json" 
        src="https://github.com/DFYRANKINGS/YOR-Construction-Schema-Markup/blob/main/locations/van-nuys/schema.json">
</script>
