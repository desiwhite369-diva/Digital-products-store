# Digital Products Store — repo bootstrap

This repository is a starter template for a digital products store using GitHub to host the storefront and product metadata.

Goals
- Store product metadata and source assets
- Publish a static storefront (GitHub Pages or other static host)
- Support automated deployments and release flow
- Provide room to integrate payments (Gumroad/Payhip/Paddle/Stripe + serverless)

Quick start
1. Choose an option:
   - Quick: Use GitHub Pages + Gumroad/Payhip links (fastest)
   - Mid: Static site + Stripe + serverless functions (best control)
   - Full: Custom storefront app (Next.js + Stripe)
2. Add your product files in `products/assets/` and metadata in `products/products.yml`.
3. Edit `site/` to create your storefront (simple HTML or static site generator).
4. Enable GitHub Pages: Settings -> Pages -> Source -> `gh-pages` branch (or `main`/`docs` depending on workflow).
5. If using Stripe, deploy serverless functions in `serverless/` to issue protected download links.

Files of interest
- products/products.yml — product catalog and metadata
- site/ — static site source
- .github/workflows/publish.yml — GitHub Actions workflow to build and publish site

License
- This repo uses the MIT license by default. Change as needed.

Next steps
- Answer the questions in the top-level issue to pick a flow (I can generate the storefront code + actions next).
