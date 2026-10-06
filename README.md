# Fidget Clicker Store

A lightweight, static e-commerce storefront for tactile mechanical-key clicker fidgets. The site is designed to run directly from GitHub Pages with no build step or framework.

## Included

- Responsive, playful single-page storefront
- Shop navigation for Shop, Bundles, Build Your Own, About, and FAQ
- 1-key, 2-key, 3-key, and 4-key clicker products with product images
- Sliding cart drawer
- Add, remove, and quantity controls
- Cart persistence with `localStorage`
- Bundle add-to-cart actions
- Build Your Own configurator for 1–4 keys, Clicky/Creamy switch feel, and 11 keycap styles per key position
- Checkout summary flow

## Files

- `index.html` — layout, responsive styles, storefront sections, cart drawer markup
- `app.js` — product catalog, cart state, localStorage syncing, rendering, and interactions
- Product and keycap images are embedded directly in `app.js`, so GitHub Pages still needs only the three core files.

## Run locally

Because the project is fully static, you can open `index.html` directly in a browser. For the closest match to GitHub Pages behavior, use any simple local web server.

## Payments / checkout

The cart and checkout summary work without a backend. To accept real payments, create a hosted checkout/payment link with your payment provider and paste its URL into `CHECKOUT_URL` near the top of `app.js`.

## GitHub Pages

Configure GitHub Pages to deploy from the `main` branch and the repository root (`/`). The expected project-site URL is:

`https://clickerlabstore.github.io/FidgetClickerStore/`
