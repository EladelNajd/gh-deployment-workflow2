# GitHub Actions Deployment Workflow

This repository demonstrates how to use GitHub Actions to automatically deploy a static website to GitHub Pages.

## Features

- Automatic deployment to GitHub Pages when changes are made to `index.html`
- Simple workflow configuration using GitHub Actions
- Conditional deployment based on file changes

## How It Works

The repository contains a GitHub Actions workflow (`.github/workflows/deploy.yml`) that:

1. Triggers when changes are pushed to the main branch
2. Checks if the `index.html` file was modified
3. If modified, deploys the website to GitHub Pages

## Getting Started

1. Fork this repository
2. Enable GitHub Pages in your repository settings:
   - Go to Settings > Pages
   - Set the source to "GitHub Actions"
3. Make changes to the `index.html` file
4. Push your changes to the main branch
5. GitHub Actions will automatically deploy your website

Your site will be available at `https://<your-username>.github.io/gh-deployment-workflow2/`

## Technologies Used

- HTML/CSS
- GitHub Actions
- GitHub Pages