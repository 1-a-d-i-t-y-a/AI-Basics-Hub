[README.md](https://github.com/user-attachments/files/32666842/README.md)
# AI Basics Hub — Digital Marketing Project

GitHub-ready static portfolio/documentation site for the **AI Basics Hub** Digital Marketing internship project.

## What is included

- Responsive static project website (`index.html`)
- CSS and JavaScript in `assets/`
- Eight reconstructed evidence screenshots
- Complete project documentation in `docs/AI_Basics_Hub_Digital_Marketing_Project.md`
- Project metadata in `data/project.json`
- GitHub Pages support via `.nojekyll`
- Optional GitHub Actions workflow in `.github/workflows/pages.yml`

## Evidence note

This repository intentionally distinguishes **planned/documented work** from live platform results. Google Ads and email marketing are shown as planning artifacts and are explicitly marked as not launched/not sent. Search Console/analytics screens are reconstructed project evidence and should not be interpreted as historical traffic data.

## Deploy with GitHub Pages

### Option A — simplest: deploy from the repository branch

1. Create a new GitHub repository, for example `ai-basics-hub-digital-marketing`.
2. Upload all files from this folder to the repository root.
3. Commit and push to the default branch.
4. Open **Settings → Pages**.
5. Choose **Deploy from a branch**, select the default branch and `/ (root)`, then save.

### Option B — GitHub Actions

The repository also contains `.github/workflows/pages.yml`. When Pages is configured to use GitHub Actions, pushes to `main` can deploy the static site automatically.

The site is plain HTML/CSS/JS, so no Node.js or build step is required.
