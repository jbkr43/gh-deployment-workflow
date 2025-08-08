# jbkr43.github.io – Roadmaps.sh Project

This repository hosts a simple DevOps-themed landing page for a [roadmap.sh](https://roadmap.sh) project, automatically deployed to GitHub Pages using GitHub Actions.

## 🚀 Features

- **Automatic Deployment:** Changes to `index.html` are deployed when a pull request is merged into the `main` branch.
- **CI/CD Workflow:** Uses GitHub Actions for continuous integration and deployment.
- **Live Site:** [https://jbkr43.github.io](https://jbkr43.github.io)

## 📦 Deployment Workflow

The workflow is defined in `.github/workflows/deploy.yml` and includes:

- Trigger on pull request merge to `main` when `index.html` changes
- Checkout repository
- Setup GitHub Pages
- Upload site artifact
- Deploy to GitHub Pages

## 🛠️ Usage

1. Edit `index.html` with your roadmap or content.
2. Create a pull request to the `main` branch.
3. Merge the pull request.
4. The site will be automatically updated via GitHub Actions.

## 🔗 Links

- [Roadmap.sh](https://roadmap.sh)
- [GitHub Pages Settings](https://github.com/jbkr43/jbkr43.github.io/settings/pages)
- [GitHub Actions Workflow](./.github/workflows/deploy.yml)
- [Your GitHub Profile](https://github.com/jbkr43)

---

Powered by GitHub Actions