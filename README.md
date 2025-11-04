# Project Skeleton for Don’t Die Gloriously

This template repository provides a consistent starting point for new projects under the **Don’t Die Gloriously** (DDG) umbrella.  By following the same structure and processes across projects, we ensure that documentation, collaboration, security and licensing are clear from day one.

## What's included

This skeleton includes a collection of files and settings that reflect best practices from the GitHub documentation and open source community:

- **Documentation** – A `docs/` folder with example pages and a GitHub Actions workflow that builds and deploys the site to GitHub Pages.  To use a custom domain, either add the domain in the Pages settings (which generates a `CNAME` file) or edit `docs/CNAME` manually.
- **Issue templates** – Bug report and feature request templates in `.github/ISSUE_TEMPLATE` plus a configuration file that disables blank issues and directs contributors to the appropriate templates.
- **Pull request template** – A template that guides contributors to describe their changes, link to relevant issues and tick off checklist items.
- **Code of Conduct** – A code of conduct based on the Contributor Covenant v2.1, establishing expectations for respectful collaboration.
- **Contributing guidelines** – A `CONTRIBUTING.md` file that describes how to report bugs, suggest new features, run the project locally and submit pull requests.
- **Security policy** – A `SECURITY.md` file explaining how to report vulnerabilities and which versions are supported.
- **License** – The MIT License, granting broad permission to use, modify and distribute the software with a disclaimer of warranty.
- **Citation metadata** – A `CITATION.cff` file with placeholders for your project name, version, release date and authors.  GitHub uses this file to generate a “Cite this repository” link.
- **`.gitignore`** – A file covering common compiled files, virtual environments and editor artefacts so they are not committed.
- **Configuration stubs** – Placeholder files such as `CHANGELOG.md`, `SUPPORT.md` and `.github/CODEOWNERS` to be customised for each project.

## Recommended folder structure

| Folder | Description |
| --- | --- |
| `src/` | Source code for your project. |
| `test/` | Unit or integration tests. |
| `docs/` | Markdown documents that are built and published via GitHub Pages. |
| `.github/` | Repository metadata for issues, pull requests, workflows and ownership. |
| `.config/`, `.build/`, `dep/`, `res/`, `samples/`, `tools/` | Optional directories for configuration files, build outputs, dependencies, resources, sample data and scripts. |

## Getting started

1. **Create a new repository** on GitHub from this template.
2. **Replace placeholder text** in all files – update the project name, description, authors, contact email, website and links.  Edit the `CITATION.cff` file to reflect the correct version, release date and DOI.
3. **Enable GitHub Pages** in the repository **Settings → Pages**. 2. Under **Build and deployment**, set **Source = GitHub Actions**. 3. The workflow `.github/workflows/pages.yml` handles deployments automatically.
4. **Configure a custom domain** if needed.  Add your domain in the GitHub Pages settings to generate a `CNAME` file automatically, or edit `docs/CNAME` manually.
5. **Enable security features**: turn on Dependabot alerts and updates, secret scanning, push protection, code scanning and branch protection rules via the repository settings.
6. **Modify workflows** as needed to build your code, run tests or publish packages.

## Repository settings

GitHub strongly recommends enabling the following settings to improve security and collaboration:

- **Dependabot alerts and updates** – Receive alerts about vulnerable dependencies and let Dependabot automatically propose updates.
- **Secret scanning** – Detect secrets such as API keys or passwords in your commits and stop them before they are pushed; enable push protection to block accidental leakage.
- **Code scanning** – Run security and code quality analyses on your code.
- **Branch protection rules** – Protect the default branch by requiring pull request reviews, requiring status checks to pass before merging and preventing force pushes.

## Licensing

- **Code / hardware / firmware:** PolyForm Noncommercial 1.0.0  
  (see [LICENSE.md](./LICENSE.md))
- **Docs / research:** CC BY-SA 4.0  
  (see [docs/LICENSE_DOCS.md](./docs/LICENSE_DOCS.md))
- **Commercial use:** requires a separate agreement  
  (see [COMMERCIAL_LICENSE.md](./COMMERCIAL_LICENSE.md))

[![License: PolyForm NC 1.0.0](https://img.shields.io/badge/License-PolyForm%20NC-blue)](https://polyformproject.org/licenses/noncommercial/1.0.0/)
[![Docs: CC BY-SA 4.0](https://img.shields.io/badge/Docs-CC%20BY--SA%204.0-lightgrey)](https://creativecommons.org/licenses/by-sa/4.0/)

## Community & Support
- 💬 **Chat & questions:** [![Discord](https://img.shields.io/badge/Discord-Join%20the%20server-blue)](https://discord.dontdiegloriously.com) https://discord.dontdiegloriously.com
- 🐛 **Bugs & features:** open a GitHub Issue (use the templates)
- 🔐 **Security:** see [SECURITY.md](./SECURITY.md) — email, not Discord

## Notes

- Add or remove files as needed; the goal is to provide a consistent starting point rather than a one‑size‑fits‑all solution.