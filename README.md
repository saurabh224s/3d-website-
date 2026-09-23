# The AI Toolshelf

A no-build 3D bookshelf powered by an optional Google Sheet.

## Run locally

`python -m http.server 4322`

Open `http://localhost:4322/`.

## Configuration

Set `sheet` in `config.js` for live Google Sheet data. When it is empty, the app can use checked-in CSV data. Keep private spreadsheet URLs and credentials out of source control.

## Deploy

This is a static site and can be deployed to GitHub Pages, Netlify, Vercel, or another static host.
