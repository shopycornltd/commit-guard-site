# Commit Guard Public Site

This repository hosts the public website for **Commit Guard**, the workflow-driven AI code review plugin for IntelliJ by **Shopycorn Ltd**.

It exists separately from the private product repository so we can keep the plugin source private while still publishing:

- a public product landing page
- the Developer EULA
- the Privacy Notice
- JetBrains Marketplace-friendly public links

## Live Site

Expected GitHub Pages URLs:

- Site: `https://shopycornltd.github.io/commit-guard-site/`
- EULA: `https://shopycornltd.github.io/commit-guard-site/eula/`
- Privacy: `https://shopycornltd.github.io/commit-guard-site/privacy/`

## Repository Structure

- `index.html`
  Public landing page
- `assets/`
  Shared CSS, logo, and promo imagery
- `eula/index.html`
  Developer EULA
- `privacy/index.html`
  Privacy Notice
- `.github/workflows/pages.yml`
  GitHub Pages deployment workflow

## GitHub Pages

This repo is designed for **GitHub Actions**-based Pages deployment.

The workflow:

1. checks out the repo
2. stages the static files into `_site/`
3. uploads the Pages artifact
4. deploys to GitHub Pages

To use it:

1. keep this repository public
2. in GitHub, open `Settings -> Pages`
3. set `Source` to `GitHub Actions`
4. push to `main` or run the Pages workflow manually

## Related Repositories

- Product repository: [github.com/shopycornltd/commit-guard-ai](https://github.com/shopycornltd/commit-guard-ai)

## Support

- Vendor: Shopycorn Ltd
- Contact: [shopycornltd@gmail.com](mailto:shopycornltd@gmail.com)
