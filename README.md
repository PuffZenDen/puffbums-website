# Puffbums Website

Static one-page Puffbums product-led website for `www.puffbums.com`.

## Asset labels

| File | Suggested use |
| --- | --- |
| `assets/images/puffbums-logo.png` | Main website logo and favicon source |
| `assets/images/hero-lifestyle-oceanbum.jpg` | Hero image |
| `assets/images/product-closeup-oceanbum.jpg` | Product close-up / Oceanbum detail |
| `assets/images/tactile-squeeze-oceanbum.jpg` | Tactile-led breathing / squeeze section |
| `assets/images/desk-focus-oceanbum.jpg` | Work/focus reset section |
| `assets/images/bedside-calm-oceanbum.jpg` | Meet Oceanbum / bedtime calm section |
| `assets/images/founder-bundle-oceanbum.jpg` | Founder Bundle product card |
| `assets/images/box-hand-oceanbum.jpg` | Gallery / packaging proof |
| `assets/images/box-desk-oceanbum.jpg` | Gallery / desk environment |
| `assets/images/box-coastal-oceanbum.jpg` | Replacement product card / packaging hero |
| `assets/images/still-calm-oceanbum.jpg` | Gallery / calm still-life |

## Current Shopify links

These are the live Shopify product URLs currently used by the website

- Oceanbum Founder Bundle: `https://puffzenden.com/products/oceanbum-founder-bundle`
- Oceanbum Replacement: `https://puffzenden.com/products/oceanbum-replacement`

## GitHub Pages deployment

1. Upload all files in this folder to the root of the `puffbums-website` repo.
2. Go to **Settings → Pages**.
3. Choose **Deploy from a branch**.
4. Select your main branch and `/root` folder.
5. Add the custom domain: `www.puffbums.com`.
6. Enable **Enforce HTTPS** after GitHub confirms DNS.

## DNS guide

For the `www` subdomain, create a CNAME record:

- Host/name: `www`
- Type: `CNAME`
- Value/target: `puffzenden.github.io`

For the root domain `puffbums.com`, either set forwarding to `https://www.puffbums.com` from your domain provider or add GitHub Pages apex A records if you want the root domain to resolve directly.
