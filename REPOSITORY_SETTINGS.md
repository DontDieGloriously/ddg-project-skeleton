# Recommended GitHub Repository Settings

This document lists configuration settings that we recommend you enable in your GitHub repository to follow best practices for open source projects.  While this template cannot change repository settings for you, the guidance below will help you configure your project after creation.

## Security features

GitHub offers several automated security checks that can be enabled through your repository settings.  Enabling these features helps protect projects and its users【70583929786251†L179-L197】:

- **Dependabot alerts** – Receive alerts when your dependencies contain known vulnerabilities and view suggested upgrades.
- **Dependabot security updates** – Automatically open pull requests to update vulnerable dependencies.
- **Secret scanning** – Scan for secrets like API keys or credentials that may have been committed.  Enable **push protection** to prevent secrets from being pushed to the repository.
- **Code scanning** – Run security analysis on your code using GitHub’s code scanning tools or third‑party providers.

## Branch protection rules

Protecting your default branch ensures that changes are reviewed and tested before they are merged.  GitHub recommends setting up branch protection rules on your default branch【70583929786251†L210-L219】.  Typical rules include:

- Require pull request reviews before merging.
- Require status checks to pass (e.g. linting, unit tests, code scanning) before merging.
- Require signed commits if your project enforces commit signing.
- Restrict force pushes and deletion of the branch.
- Require linear history to prevent merge commits, if you prefer a linear Git history.

## Pages configuration

If you plan to publish documentation via GitHub Pages, go to **Settings → Pages** and select the **Source = GitHub Actions** option.  If you add a custom domain, GitHub will automatically create a `CNAME` file or you can edit `docs/CNAME` yourself.

## Additional suggestions

- **Choose a license** – This template uses the MIT License by default, but you can change it if necessary.  Choose a license early to clarify usage rights.
- **Enable Discussions** – Create a space for users to ask questions and discuss ideas without cluttering the issue tracker.
- **Enable Wiki** – Use the wiki for architecture diagrams, design documents or other long‑form documentation if needed.
- **Set up automated workflows** – Use GitHub Actions to automate tests, builds and releases.  The `pages.yml` workflow in this template shows how to deploy documentation using Pages【493724707146630†L90-L151】.
- **Pin important issues** – Pin guidelines like the Code of Conduct and contribution guidelines to the top of the issues list for easy discovery.