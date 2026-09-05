# AYT — Landing Page

First-draft marketing site for **AYT Service**, built around the AYT logo. Single self-contained HTML file — no build step, no dependencies to install.

## What's here

- `index.html` — the full landing page (styles, fonts, and the logo are all inlined, so this one file is the whole site)

## Preview locally

Just open `index.html` in a browser, or serve it:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deploying with GitHub Pages

1. Push this repo to GitHub (see commands below).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
4. Save — GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/` within a minute or two.

## Sections on the page

- Hero
- Who it's for (D2C brands vs. insurance/BFSI businesses)
- How it works (4 steps)
- Proof — GraceKart, an AYT Service client
- Pricing (draft numbers — not final)
- About
- Final call to action

Treat copy, pricing, and the CTA email address as placeholders to edit before this goes live.

## Pushing to your own GitHub

This repo is already initialized locally with one commit. To get it onto GitHub:

```bash
# 1. Create a new EMPTY repository on github.com (no README/license/gitignore) — call it e.g. "ayt-website"

# 2. From inside this folder, point it at your new repo and push:
git remote add origin https://github.com/<your-username>/ayt-website.git
git branch -M main
git push -u origin main
```
