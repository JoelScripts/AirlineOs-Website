# Airline OS — website

Public marketing site + devlog for **Airline OS**, an airline life layer for
Microsoft Flight Simulator 2024.

- `index.html` — landing page: features, universal engine, roadmap/timeline, teaser, buy section
- `legal.html` — copyright, trademarks, third-party notices, privacy
- `devlog/` — progress updates
- `style.css` / `assets/` — design system and media
- `LICENSE` — proprietary, all rights reserved
- `.github/workflows/deploy-site.yml` — deploys to GitHub Pages on push to `main`

## Adding a devlog post

1. Copy `devlog/001-introducing-airline-os.html` to `devlog/002-<slug>.html`, edit content
2. Add a card at the top of the post list in `devlog/index.html`
3. Add a preview card to the homepage section `#devlog`
4. Push to `main`

## Publishing

GitHub → Settings → Pages → Source: **GitHub Actions**.
Every push to `main` goes live automatically.

## Preview locally

Open `index.html` in a browser — no build step, no dependencies.

---

© 2026 Airline OS. All rights reserved — see [`LICENSE`](LICENSE) and [`legal.html`](legal.html).
Microsoft Flight Simulator 2024 is a product of Microsoft Corporation and Asobo Studio.
Airline OS is an independent third-party add-on, not affiliated with Microsoft or Asobo.
