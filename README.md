# Commit Guard Public Site

This repository hosts the public website for **Commit Guard**, the workflow-driven AI code review and commit-message automation plugin for IntelliJ by **Shopycorn Ltd**.

It exists separately from the private product repository so we can keep the plugin source private while still publishing:

- a public product landing page
- the Developer EULA
- the Privacy Notice
- the public security policy summary
- JetBrains Marketplace-friendly public links

The public landing page highlights:

- workflow-driven AI review
- IntelliJ commit message generation
- terminal commit gating and managed commit-message prefills
- local and cloud provider support

## Live Site

Expected GitHub Pages URLs:

- Site: `https://shopycornltd.github.io/commit-guard-site/`
- EULA: `https://shopycornltd.github.io/commit-guard-site/eula/`
- Privacy: `https://shopycornltd.github.io/commit-guard-site/privacy/`
- Security: `https://shopycornltd.github.io/commit-guard-site/security/`

## Repository Structure

- `index.html`
  Public landing page
- `assets/`
  Shared CSS, logo, and promo imagery
- `eula/index.html`
  Developer EULA
- `privacy/index.html`
  Privacy Notice
- `security/index.html`
  Public security reporting and support page
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
