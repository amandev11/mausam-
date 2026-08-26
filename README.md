# Mausam

Premium, intelligent weather experience for web/mobile.

## What is included
- Atmospheric weather homepage
- Personalized "Today for you" recommendations
- Human ↔ Precise presentation toggle
- Smart scores: Outdoor, Running, Comfort, Air
- Hourly chart + daily forecast
- UV, humidity, wind, air-quality proxy, visibility and pressure cards
- Weather map presentation layer
- Saved places + Open-Meteo geocoding search
- Insights page
- Settings for units, personality and presentation mode
- Offline shell via service worker
- Responsive / Android-first CSS with reduced-motion support

## Data
The demo uses Open-Meteo by default so it can run without an API key.
An optional `config.js` field exists for future provider integration. Never put a production secret in a public client bundle; proxy private weather keys through a server/serverless function.

## Run
Because this is a zero-build static app, any static server works:

```bash
python -m http.server 4173
```

Then open `http://localhost:4173`.

## GitHub
This folder is intentionally GitHub-ready. Add your repository as `origin` and push the contents.
