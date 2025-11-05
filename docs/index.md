# Project documentation

Welcome to the documentation for your project based on the **Don’t Die Gloriously** skeleton.  This site is generated from the Markdown files in the `docs/` directory and published to GitHub Pages.

## How it works

GitHub Pages can publish content from a folder on the default branch.  This template uses a custom workflow (`.github/workflows/pages.yml`) to copy the Markdown files from `docs/` into a `_site/` directory and deploy them via the `upload-pages-artifact` and `deploy-pages` actions.

To preview your documentation locally, you can open these Markdown files in any Markdown viewer.  When you push changes to the `docs/` folder, the workflow will rebuild and republish the site automatically.

If you wish to use a custom domain, edit the `CNAME` file in this directory or configure the custom domain in the repository’s Pages settings.
