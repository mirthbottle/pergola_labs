# pergola_labs

Homepage for Pergola Labs, a data engineering consultancy for climate tech.

Pure static site (`index.html` + `styles.css` + `og-image.png`) — no build step.

## Deploy to GitHub Pages

Option A — workflow (included): push this repo's `main` branch; `.github/workflows/pages.yml` publishes the repo root automatically after you set **Settings → Pages → Build and deployment → Source: GitHub Actions** once.

Option B — classic branch: push these files to a `gh-pages` branch and select it in Settings → Pages.

Local preview: `python3 -m http.server 8000`, then open http://localhost:8000.
