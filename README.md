# Furever Happy Shopify Theme

Initial Shopify Online Store 2.0 theme scaffold for **Furever Happy**.

This repository is structured like a Dawn-compatible Shopify theme so it can be edited in Shopify's theme editor and expanded with products, collections, and brand design later.

## What's included

- Working Shopify theme layout
- Homepage JSON template
- Editable hero, story, and product preview sections
- Basic placeholder styling for the first storefront preview
- Shopify-ready config, locale, and asset folders

## Next steps

1. Use the GitHub repository `Neel57646/FHAUS`.
2. Keep these files pushed to the repository.
3. Install or open Shopify CLI.
4. Connect to the existing Shopify store:

```powershell
shopify theme dev --store your-store.myshopify.com
```

5. When the preview looks correct, upload the theme:

```powershell
shopify theme push --unpublished --store your-store.myshopify.com
```

## Notes

- Store credentials and store URL are intentionally not committed.
- This first version is functional scaffolding, not final brand design.
- The theme can be replaced with a full Dawn checkout later while preserving the Furever Happy sections and templates.
