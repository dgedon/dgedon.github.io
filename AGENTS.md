# AGENTS.md — Daniel Gedon's Personal Website

Source for [dgedon.github.io](https://dgedon.github.io).

Plain HTML + CSS static site, served directly by GitHub Pages (no Jekyll, no build step).

---

## Repository structure

| Path | Purpose |
|------|---------|
| `index.html` | Entire website (single page) |
| `style.css` | All styles: colors, layout, typography, dark/light themes |
| `.nojekyll` | Disables Jekyll processing on GitHub Pages |
| `assets/profile.jpg` | Profile photo |
| `assets/cv.pdf` | CV PDF |

---

## Key conventions

### Updating content

All content lives in `index.html`. Edit it directly and push to deploy.

### Adding a selected paper

Find `<div class="papers">` in `index.html` and add:

```html
<div class="paper">
  <div class="paper-title">Paper Title</div>
  <div class="paper-meta">Author et al. &nbsp;·&nbsp; Venue Year</div>
  <div class="paper-links">
    <a href="https://arxiv.org/abs/..." target="_blank" rel="noopener">arXiv</a>
    <a href="https://github.com/..." target="_blank" rel="noopener">Code</a>
  </div>
</div>
```

### Updating the CV

Replace `assets/cv.pdf` in place, or swap the file and update the `href` on the `<a class="cv-link">` element in `index.html`.

### Dark / light theme

Colors are CSS custom properties in `style.css`:
- `:root` — dark mode defaults
- `:root.light` — light mode overrides

The toggle button in `index.html` switches a `light` class on `<html>` and saves to `localStorage`.

---

## Local preview

Open `index.html` directly in a browser — no server needed.

Or run a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

---

## Deployment

Push to `master`. GitHub Pages deploys automatically within ~1 minute.
- Live site: <https://dgedon.github.io>
- GitHub repository: `dgedon/dgedon.github.io`
