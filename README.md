# Tiny Shop

A tiny store with a product list, a cart and checkout. Everything runs in the browser; `server.js` only serves the files in `public/`. No dependencies.

```bash
npm start          # http://localhost:4100
PORT=5000 npm start
```

What the store is supposed to do is written down in [PRD.md](PRD.md).

## Layout

- `public/index.html`: the page
- `public/products.js`: the catalog
- `public/pricing.js`: cart math (line totals, shipping, totals)
- `public/app.js`: the storefront UI (product list, cart, checkout)
- `public/style.css`: styles
- `server.js`: static file server for local development
