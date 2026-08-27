# SONKEI CO. — Website

A static, responsive front-end for the SONKEI CO. brand: homepage, shop/collection page, a product detail page, and a bonus brand-pack reference page. Plain HTML/CSS/JS — no build step, no dependencies.

## Files

- `index.html` — homepage
- `shop.html` — Dry-Fit collection / shop grid
- `product.html` — Long-Sleeve Dry-Fit product page
- `brand.html` — brand pack reference (logo, colours, type, packaging concepts)
- `styles.css` — shared styles
- `script.js` — mobile nav toggle + small product-page interactions
- `images/` — all photography and logo assets

## Publish it on GitHub Pages (free, no domain needed)

1. Go to [github.com/new](https://github.com/new) and create a new repository (e.g. `sonkei-co`). Keep it **Public** (GitHub Pages on the free plan needs a public repo, unless you're on a paid plan).
2. On the new repo's page, click **uploading an existing file**.
3. Drag in every file and folder from this package (`index.html`, `shop.html`, `product.html`, `brand.html`, `styles.css`, `script.js`, and the whole `images` folder), then click **Commit changes**.
4. In the repo, go to **Settings → Pages**.
5. Under **Build and deployment → Source**, choose **Deploy from a branch**. Under **Branch**, pick `main` and folder `/ (root)`, then **Save**.
6. Wait a minute or two, then refresh — GitHub will show your live URL, something like:
   `https://<your-username>.github.io/sonkei-co/`

That URL is free and works with no domain of your own. You can point a real domain at it later (Settings → Pages → Custom domain) whenever you buy one.

## Notes

- All copy, prices and product details are placeholders drawn from the brand brief — swap in real ones before launch.
- Images are the campaign photography you supplied, cropped for web use.
- The nav, "You May Also Like" links, and filters are visual/UI only — there's no cart or checkout logic behind them yet.
