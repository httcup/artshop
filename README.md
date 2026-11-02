# artshop

Hand-textured wall art storefront prototype (brand placeholder: **Terra & Tone Studio**).

Structure is cloned from a Shopify DTC reference site in the same category (textured abstract wall art, US market):
announcement bar → nav → hero → best sellers → collections → shop-by-space → 4-step made-to-order flow →
craft story → reviews → limited-time CTA → trust icons → footer (with trade / wholesale entry).

## Stack

- Static HTML + CSS only (`index.html`), no build step
- Images in `images/` (AI-generated assets, free to replace)

## Deploy

Connected to **Cloudflare Pages** (`artshop-store`), production branch `main`.
Every push to `main` triggers an automatic build and deploy.

- Production URL: https://artshop-store.pages.dev
- Mirror: https://httcup.github.io/artshop/ (GitHub Pages)

## Edit locally

Just open `index.html` in a browser. All copy is in English, prices in USD.

## Before going live for real

1. Replace the placeholder brand name, logo and colours
2. Swap AI images for real product photography where possible
3. Add the missing policy pages: FAQ, Shipping & Returns, Privacy, Terms
4. Connect a real checkout (Shopify / Stripe Payment Links) or turn the CTA into an inquiry form
5. Point a custom domain in Cloudflare Pages → Custom domains
