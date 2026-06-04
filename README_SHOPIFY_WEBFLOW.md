# Smoketree Hot Sauce Co. — Two-Sauce Website Package

This package restores the original website copy and focuses the storefront on the two Phase 1 sauces only:

- Classic Datil Hot Sauce
- Smoked Datil Hot Sauce

## Editable areas
Search `EDITABLE` in `index.html` to find copy, image paths, product data, checkout settings, and contact fields.

## Storefront settings
At the top of `index.html`:

- `SHOP_ENABLED = false` keeps the site in coming-soon / inquiry mode.
- `CHECKOUT_MODE` can be changed to `inquiry`, `stripe`, `shopify`, or `webflow` once checkout URLs are ready.

## Product data
Product data is duplicated in:

- `index.html` for the live page
- `assets/product-data.json` for integrations
- `products-shopify-webflow.csv` for import/reference

Only the two main sauces are included. Jelly and BBQ products have been intentionally removed from the current site focus.
