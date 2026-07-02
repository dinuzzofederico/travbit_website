# Travbit — Website

Marketing landing page for **Travbit**, the travel itineraries, maps & city guides app.

> Your itineraries, mapped and told.

## Stack

Plain **HTML + CSS** — no build step. Cloudflare Pages serves the files directly.

```
index.html          # the landing page
styles.css          # all styles (brand sunset gradient)
assets/img/         # logo, product icons, OG image
```

## Local preview

Just open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8080
# then open http://localhost:8080
```

## Deploy (Cloudflare Pages)

Connected to GitHub repo `dinuzzofederico/travbit_website`. Because there's no build:

- **Build command:** *(leave empty)*
- **Build output directory:** `/` (root)

Every push to `main` triggers a deploy.

## To do / notes

- Swap the CSS phone mockup for real app screenshots when available.
- Wire the App Store / Google Play badge links once store URLs are live.
- Add `/privacy` and `/terms` pages (footer links are placeholders).
- Point the custom domain (GoDaddy DNS → Cloudflare) when ready.
