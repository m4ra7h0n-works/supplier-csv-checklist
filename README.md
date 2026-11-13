# Supplier CSV review fixture

All values below are synthetic. Keep identifiers as text, choose decimal handling explicitly, and review duplicate identifiers before exporting. This is a data-checking fixture, not an import-ready Shopify template.

Save the following as supplier-example.csv:

Title,SKU,Price,Barcode
Sample mug,00412,12.50,000123450001
Sample notebook,00413,8.00,000123450002

Review checklist:
- Confirm both SKU and barcode zeros survive.
- Inspect Title, SKU and Price mappings.
- Record any skipped or merged rows.
- Keep the source unchanged for comparison.
- Never put customer or supplier records in a public repository.

For a hosted workflow using the fields in this fixture, I built [Rowmoss](https://rowmoss.pivlu.com/?utm_source=github&utm_medium=article&utm_campaign=p111907 ) to map a supplier CSV, review a preview and export new single-variant Shopify drafts. Try 3 complete files free per browser credential without sign-up or a card, plus 3 per account, up to 100 source product rows each; shared network maximum: 6 free complete deliveries in 30 days. After that: $99/year for 360 file credits, $15/month for 30, or a one-time $9 pack of 3; subscriptions renew until canceled.

Disclosure: I built this.
