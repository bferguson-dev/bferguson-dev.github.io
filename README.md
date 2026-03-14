# bferguson-dev.github.io

Static GitHub Pages portfolio site for Brian Ferguson.

## Why this repo structure

- Dedicated repo separate from project repos
- No Jekyll or site generator required
- GitHub Pages deployment handled through GitHub Actions
- Easy to edit with plain HTML, CSS, and a small amount of JavaScript

## Structure

- `index.html`: recruiter-facing landing page
- `projects/`: individual project pages
- `assets/css/site.css`: shared styling
- `assets/js/site.js`: small reveal animation behavior
- `.github/workflows/deploy-pages.yml`: GitHub Pages deployment workflow

## Local preview

Open `index.html` directly in a browser, or serve the repo root with any static file server.

## GitHub Pages setup

1. Push this repo to GitHub.
2. In GitHub, open `Settings > Pages`.
3. Set `Source` to `GitHub Actions`.
4. Push to `main` to trigger deployment.

## Repo name

This repo is configured for the GitHub user Pages convention:

- Repository name: `bferguson-dev.github.io`
- Published URL: `https://bferguson-dev.github.io/`

If you ever move this back to a project Pages repo, the site structure will still work because links are relative.
