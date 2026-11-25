# Ventas con Propósito — shop-the-list pages

Static, mobile-first pages for the Pinterest roundup pins.

## Pages

- `index.html` — all lists
- `must-haves-for-women/` — Amazon Must-Haves for Women
- `finds-id-buy-again/` — Amazon Finds I'd Buy Again
- `christmas-gifts-her-under-50/` — Christmas Gift Guide for Her Under $50
- `baby-toys/` — Holiday Baby Toys
- `toddler-toys/` — Holiday Toddler Toys

Every "Shop on Amazon" button uses `https://www.amazon.com/dp/<ASIN>?tag=cventasconpro-20`, `target="_blank"`, and `rel="sponsored nofollow noopener"`.

## Product images (Associates rules)

These pages do **not** host or hotlink Amazon product photographs.

Each product card uses an original photorealistic lifestyle photo of the real product (AI-generated from official or retailer reference photos, then accuracy-checked). The files live in each list’s `img/` folder as web-optimized JPEGs (800px wide, under 150 KB). They are not copies of Amazon’s Product Advertising images.

Amazon's Associates Program IP License (updated April 14, 2026) says Product Advertising Content, including images, must be obtained by calling the **Creators API** or **PA API** (or an approved Data Feed). You may not store or cache Amazon image files; you may only store an API image URL for up to 24 hours and then refresh it. Scraped or downloaded `m.media-amazon.com` files, and unofficial hotlinks, are not a licensed source.

Prices are not shown on the pages. A note says prices appear on Amazon and may change.

## Deploy

This folder is the site root (there is no `dist` or `build` folder). Point GitHub Pages, Cloudflare Pages, Netlify, or Surge at `/workspace/shop-pages/`.
