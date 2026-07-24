# Daniel Agbaji — Professional Portfolio

Industry-standard personal site for [danielagbaji.github.io](https://danielagbaji.github.io/), rebuilt as a consulting- and hiring-ready portfolio for AI / ML / software engineering work.

## What’s included

- Full-bleed hero with clear personal brand and CTA
- Selected production AI / ML / enterprise systems
- Professional experience timeline
- Research highlights with citation signals and book credit
- Education, fellowship recognition, and contact pathways
- Responsive layout, accessible navigation, and light scroll motion

## Local preview

```bash
cd danielagbaji-portfolio
python3 -m http.server 8080
```

Open [http://localhost:8080](http://localhost:8080).

## Deploy to GitHub Pages

This folder is meant to replace the contents of the existing Pages repo [`DanielAgbaji/DanielAgbaji.github.io`](https://github.com/DanielAgbaji/DanielAgbaji.github.io).

### Option A — Push this project as the Pages site

```bash
cd danielagbaji-portfolio
rm -rf _legacy
git init
git add index.html css js assets README.md
git commit -m "Rebuild professional portfolio site"
git branch -M master
git remote add origin https://github.com/DanielAgbaji/DanielAgbaji.github.io.git
git push -u origin master --force
```

> Use `--force` only if you intentionally want to replace the old Start Bootstrap template. Back up the existing repo first if you may need anything from it.

### Option B — Copy files into a local clone

```bash
git clone https://github.com/DanielAgbaji/DanielAgbaji.github.io.git
# Replace site files with index.html, css/, js/, assets/ from this project
# Commit and push to master
```

GitHub Pages should serve from the `master` branch root (current repo setting). After push, allow a minute or two for [https://danielagbaji.github.io/](https://danielagbaji.github.io/) to update.

## Customize before publishing

1. Confirm phone preference (email + LinkedIn are primary CTAs today).
2. Swap `assets/profile.jpg` / `assets/hero.jpg` for newer portraits if desired.
3. Add project case-study pages or downloadable résumé PDF under `assets/` when ready.
4. Update work descriptions with metrics you are cleared to share publicly.

## Stack

Static HTML, CSS, and vanilla JavaScript — no build step required for GitHub Pages.
