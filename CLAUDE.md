# CLAUDE.md

## Project Overview

Single-page Hugo business card site for Wyoming Valley Appliance Repair.
No theme is used — the entire page is rendered from `layouts/index.html`.

## Build & Run

```bash
# Local dev server (live reload at http://localhost:1313)
hugo server

# Production build → public/
hugo
```

## Key Files

- `layouts/index.html` — the entire page template
- `static/css/style.css` — all styles; color scheme uses `--red: #c0392b`
- `hugo.toml` — site title and baseURL
- `static/images/` — place `technician.jpg` and `business-card.jpg` here

## Branch

Development branch: `claude/hugo-business-card-site-GBuE1`
