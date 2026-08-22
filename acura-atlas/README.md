# Acura Atlas — Independent Hosting Package

This folder is an independent static copy of the Ron Tonkin Acura Sales Process Atlas prepared for hosting outside ChatGPT Sites.

## Architecture
- `index.html` — shell/home page
- `styles.css` — responsive visual system
- `app.js` — search, navigation, install behavior
- `data.json` — 7 areas / 196 searchable references sourced from the original Acura sales package
- `manifest.webmanifest` + `sw.js` — installable/offline PWA support
- `_headers` — Cloudflare Pages security/cache headers

## Cloudflare Pages
Deploy this folder as a static site. No build command is required. Set the root/output directory to `acura-atlas`. Attach `atlas.acura.jordanmcdonley.com` only after the temporary Pages URL has been checked.

## Cutover rule
Do NOT delete the ChatGPT Site until the Cloudflare Pages deployment is live at the custom domain and the home page, search, one entry from every process area, and offline/install behavior have been verified.
