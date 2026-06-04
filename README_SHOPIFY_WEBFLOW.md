# Smoketree Website — Storefront Ready Package

This package includes a static HTML storefront rebuilt around transparent PNG product art.

## Files
- `index.html` — one-page website with cart drawer, product detail modals, and editable comments.
- `assets/product-data.json` — product data source for future integrations.
- `products-shopify-webflow.csv` — import/reference sheet for Shopify or Webflow CMS.
- `assets/*.png` — transparent product label assets.

## Editing
Open `index.html` and search for `EDITABLE`. Product copy, prices, image paths, checkout mode, Shopify handles, Webflow slugs, Stripe URLs, and contact details are all marked.

## Checkout modes
In `index.html`, find `CHECKOUT_MODE`. Options:
- `inquiry` — generates a prefilled email with cart details. Best before launch.
- `stripe` — uses Stripe Payment Links if you add each product's `stripeUrl`.
- `shopify` — uses each product's `shopifyHandle` as a placeholder route.
- `webflow` — uses each product's `webflowSlug` as a placeholder route.

For Shopify or Webflow, replace the placeholder checkout function with the platform-specific cart/add-to-cart embed code once your product IDs are created.
