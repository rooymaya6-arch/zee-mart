# ZEE MART

Digital products store — 110 products across 20 categories (e-books, courses, templates, presets, music, 3D models and more).

## Run it

Open `zaa-mur-digital-hub.html` in a browser, or deploy the repo as a static site on Vercel (no build step).

## Notes

- Single-file static site. Cart, wishlist and account state live in the browser (localStorage).
- Product cover images live under `assets/covers-v11/` (one 1700×1000 mockup per product, `<category>-<n>.jpg`). If that folder is missing, cards fall back to their colour/icon scene.
- Checkout is demo-mode: EasyPaisa / JazzCash / Skrill / AirTM / Neteller options are shown; no real payment is processed here.
