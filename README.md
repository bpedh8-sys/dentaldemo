# Lumire Dental Studio Website

This repository contains a static website ready for GitHub Pages deployment.

## Deploying

1. Initialize git if not already initialized:
   ```bash
   git init
   git branch -M main
   git add .
   git commit -m "Initial site and GitHub Pages workflow"
   ```
2. Create a GitHub repository and add it as a remote:
   ```bash
   git remote add origin https://github.com/<username>/<repository>.git
   git push -u origin main
   ```
3. GitHub Actions will build and publish the repository to the `gh-pages` branch.

## Notes

- The workflow file is located at `.github/workflows/deploy.yml`
- The site is served from the repository root by the action.
