# Lumae Skincare

Fictional Shopify theme for a portfolio project, built on top of Dawn. The goal is to demonstrate a premium skincare store with its own visual identity, custom Liquid sections, Online Store 2.0 templates, and case study documentation.

## What Was Built

- Custom homepage with an editorial hero, featured collection, 3-step routine, social proof, and newsletter signup.
- Collection and product templates adapted for a skincare store.
- Custom pages for "About" and "Case Study".
- Brand CSS in `assets/lumae.css`.
- Custom Liquid sections:
  - `sections/lumae-hero.liquid`
  - `sections/lumae-routine.liquid`
  - `sections/lumae-editorial.liquid`
  - `sections/lumae-proof.liquid`
- Premium palette: off-white, sage, ink, and subtle gold.
- Documentation for setting up the store and importing fictional products.

## Running With Shopify

1. Create a development store in the Shopify Partner/Dev Dashboard.
2. Install the Shopify CLI if you do not already have it.
3. In the terminal, from this project directory, run:

```bash
npx @shopify/cli@latest theme dev --store your-store.myshopify.com
```

4. In the Shopify admin, import the products from `docs/lumae-products.csv`.
5. Create the pages `About Lumae` and `Case Study`, applying the `page.about` and `page.case-study` templates.
6. Configure the main menu to point to Home, Catalog, About, and Case Study.

More details are available in `docs/SHOPIFY_SETUP.md`.

## Portfolio

Use `docs/CASE_STUDY.md` as the base for the case study copy. After publishing or previewing the store, complete the document with real screenshots of the homepage, collection, product page, cart, and institutional pages.

## Foundation

This project uses Dawn, Shopify's official reference theme for Online Store 2.0. The original license is preserved in `LICENSE.md`.
