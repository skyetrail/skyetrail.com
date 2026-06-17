# skyetrail.com

Marketing site for **Skyetrail** — AI engineering for energy and utilities, and independent technical due diligence for the investors backing them. Based in Oakland, CA.

Live at **[www.skyetrail.com](https://www.skyetrail.com)**.

## What's here

A single, self-contained static page. No framework, no build step, no template.

- **`index.html`** — the entire site. Inline CSS and a small vanilla-JS canvas renderer; the only external dependency is IBM Plex from Google Fonts.
- **`favicon.svg`** — the gradient-bars logo mark.
- **`CNAME`** — custom-domain config for GitHub Pages.

### Design system

- **Type** — IBM Plex Sans (display + body), IBM Plex Serif italic for the gradient accent.
- **Palette** — midnight field (`#070b16`) with a green → blue → violet aurora sweep (`#5ef2c4` → `#3aa6ff` → `#b07aff`); blue (`#3aa6ff`) drives buttons, links, and markers.
- **Motifs** — a *phasor stack* (phase-shifted waveforms drawn to `<canvas>`) carries the hero and contact atmosphere; a compact *gradient-bars mark* is the logo, used in the nav, footer, and favicon.

The page is one document: nav, hero, POV anchor, two pillar sections (utility AI engineering, investor diligence), a "Why Skyetrail" section, and a contact bookend.

## Local preview

It's a static file — open `index.html` directly, or serve the directory:

```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Deployment

Hosted on **GitHub Pages**, served from the `main` branch root. Pushing to `main` deploys; changes go live within a minute or two. The custom domain (`www.skyetrail.com`, HTTPS enforced) is configured via `CNAME` and the repo's Pages settings.

To make a change: edit `index.html`, open a PR against `main`, merge.

## Contact

📧 [info@skyetrail.com](mailto:info@skyetrail.com)

---

© Skyetrail
