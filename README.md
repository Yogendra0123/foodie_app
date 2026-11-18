# Foodie – Online Food Ordering (frontend demo)
HTML5 + CSS3 + vanilla JavaScript. No backend, no build step.

## Run locally
1. Open the `foodie` folder.
2. Double-click `index.html`, or run `python3 -m http.server 8000` in the folder and visit http://localhost:8000.
(Font Awesome icons load from a CDN, so an internet connection is needed for icons.)

## Notes
- Cart is saved in LocalStorage (key `foodie_cart`).
- Dish images are local SVGs in `assets/images/`. To use real photos, drop files there and change the `IMG()` helper in `js/script.js`.
- Checkout is a demo only; no payments.
