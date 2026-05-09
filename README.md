# Son Travels & Tours

Static single-page site for **Son Travels & Tours Limited** — a Brisbane-based travel agency specialising in curated India tour packages and worldwide flight bookings.

## Stack

Plain HTML/CSS/JS — no build step, no framework, no JS dependencies. Fonts via Google Fonts. Imagery via Unsplash. Hosted on GitHub Pages.

## Local preview

```bash
# anything that serves a directory works:
python3 -m http.server 8000
# → http://localhost:8000
```

Or just open `index.html` directly in a browser.

## Deploy

Hosted on GitHub Pages from the `main` branch root. The `.nojekyll` file disables Jekyll processing so the site is served raw.

## Contents

- `index.html` — landing page (nav, hero, India tours, flights, why us, CTA, footer)
- `.nojekyll` — bypass Jekyll on GitHub Pages
- `README.md` — this file
