# Wyoming Valley Appliance Repair

Business card website for Wyoming Valley Appliance Repair — Chris Leeds, Master Technician.

## Stack

- [Hugo](https://gohugo.io/) static site generator (v0.123.7+)
- No theme — custom single-page layout in `layouts/index.html`
- Plain CSS in `static/css/style.css`

## Project Structure

```
.
├── archetypes/         # Hugo content archetypes
├── layouts/
│   └── index.html      # Single-page layout (the whole site)
├── static/
│   ├── css/
│   │   └── style.css   # All site styles
│   └── images/         # Place image files here (see below)
├── hugo.toml           # Hugo configuration
└── public/             # Built output (gitignored)
```

## Images

Two images need to be placed in `static/images/` before building:

| Filename | Description |
|---|---|
| `technician.jpg` | Photo of technician working on a washing machine |
| `business-card.jpg` | Business card graphic with appliances |

## Development

```bash
# Serve locally with live reload
hugo server

# Build for production
hugo
```

Built output goes to `public/`.

## Deployment

Deploy the `public/` directory to any static host (Netlify, GitHub Pages, etc.).
The `baseURL` in `hugo.toml` is set to `https://www.WyomingValleyAppliance.com/`.
