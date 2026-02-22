# CLAUDE.md

## Project Overview

This is the **OnShift** umbrella company website — a static site hosted on **Cloudflare Pages**.

OnShift is the parent company behind **RotaKeep** (https://rotakeep.co.uk), a staff scheduling platform for UK hospitality businesses.

## Architecture

- **Type**: Static website (HTML, CSS, no build step)
- **Hosting**: Cloudflare Pages
- **Domain**: TBD

## File Structure

```
onshift-website/
├── index.html       # Main landing page
├── styles.css       # Site styles
└── CLAUDE.md        # Project documentation
```

## Development

Open `index.html` directly in a browser or use any local server:

```bash
python3 -m http.server 8000
```

## Deployment

Push to the connected Git repository — Cloudflare Pages will build and deploy automatically.
