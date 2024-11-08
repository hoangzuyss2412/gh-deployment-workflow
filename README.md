# File: README.md
# GitHub Pages Deployment Workflow

This repository demonstrates how to automatically deploy a static website to GitHub Pages using GitHub Actions. The workflow is triggered whenever changes are made to the `index.html` file in the main branch.

## How it works

1. The repository contains a simple static website (`index.html`)
2. A GitHub Actions workflow (`.github/workflows/deploy.yml`) monitors changes to the `index.html` file
3. When changes are detected, the workflow automatically deploys the updated website to GitHub Pages

## Setup

1. Fork this repository
2. Go to Settings > Pages
3. Under "Source", select "GitHub Actions"
4. Make changes to `index.html`
5. Push your changes to the main branch
6. Visit your site at `https://<your-username>.github.io/gh-deployment-workflow/`

## File Structure

```
├── .github/
│   └── workflows/
│       └── deploy.yml
├── index.html
└── README.md
```