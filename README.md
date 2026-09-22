# The AI Toolshelf

A no-build 3D bookshelf powered by a Google Sheet.

## Run locally

```powershell
python -m http.server 4322
```

Open http://localhost:4322/

## Google Sheets

Set `sheet` in `config.js` to a public Google Sheet URL. The app polls both configured tabs every 15 seconds and falls back to `data/Books.csv` and `data/Colours.csv` when no sheet is configured.

## Deploy

This is a static site: deploy the repository to Netlify, Vercel, GitHub Pages, or any static host.
