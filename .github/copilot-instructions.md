# GitHub Actions Deployment Workflow - Copilot Instructions

## Project Overview
This repository demonstrates a simple GitHub Actions workflow for automatically deploying static website content to GitHub Pages. The workflow is triggered when changes are made to the `index.html` file in the main branch.

## Key Components

- `index.html`: The main webpage that gets deployed to GitHub Pages
- `.github/workflows/deploy.yml`: GitHub Actions workflow configuration file that handles deployment

## Workflow Details

The GitHub Actions workflow (`deploy.yml`):
1. Is triggered only when changes to `index.html` are pushed to the main branch
2. Uses GitHub's official Pages deployment actions
3. Deploys the content to GitHub Pages with appropriate permissions

## Typical Tasks

- **Modifying the website**: Edit `index.html` to update the content
- **Updating workflow**: Modify `.github/workflows/deploy.yml` to change deployment behavior
- **Testing locally**: Open `index.html` in a browser before committing changes

## Common Commands

```bash
# Initialize a local git repository (if not already done)
git init

# Add all files to git
git add .

# Commit changes
git commit -m "Update website content"

# Push to GitHub (assuming remote is set up)
git push origin main
```

## Project Conventions

- Keep the website structure simple for this demo project
- The workflow uses path filters to only trigger on `index.html` changes
- Permissions are set to the minimum required for GitHub Pages deployment