# Handyman Yev — Business Website

Static website for **Handyman Yev**, a reliable handyman service based in Spokane, WA specializing in home repairs, remodeling, and rental property maintenance.

## Tech Stack

- **HTML** — Single-page static site
- **Tailwind CSS** — Loaded via CDN (no build step)
- **Alpine.js** — Loaded via CDN for mobile navigation toggle
- **Google Fonts** — Bitter (headings) + Source Sans 3 (body)

## Deployment

1. Push this repo to GitHub.
2. Go to **Settings > Pages**.
3. Under **Source**, select **Deploy from a branch**.
4. Set the branch to `main` and folder to `/ (root)`.
5. Save — the site will be live at `https://<username>.github.io/<repo-name>/`.

## Structure

```
handyman-yev/
├── index.html    # Full single-page website
├── images/       # Placeholder for business photos
│   └── .gitkeep
├── CNAME         # Custom domain (configure if needed)
└── README.md     # This file
```
