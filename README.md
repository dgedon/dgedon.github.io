# dgedon.github.io

Personal website for [dgedon.github.io](https://dgedon.github.io).

Plain HTML + CSS — no build step, no Jekyll, no dependencies.

## Files

| File | Purpose |
|------|---------|
| `index.html` | The entire website |
| `style.css` | All styles (colors, layout, typography) |
| `.nojekyll` | Tells GitHub Pages to skip Jekyll processing |
| `assets/profile.jpg` | Profile photo |
| `assets/cv.pdf` | CV PDF |

## How to update

### Update text content (bio, papers, links)

Edit `index.html` directly. All content is plain HTML — no template engine.

### Add a new selected paper

Find the `<div class="papers">` block in `index.html` and add a new entry:

```html
<div class="paper">
  <div class="paper-title">Paper Title Here</div>
  <div class="paper-meta">Author et al. &nbsp;·&nbsp; Venue Year</div>
  <div class="paper-links">
    <a href="https://arxiv.org/abs/..." target="_blank" rel="noopener">arXiv</a>
    <a href="https://github.com/..." target="_blank" rel="noopener">Code</a>
  </div>
</div>
```

### Update CV

Replace `assets/cv.pdf` with the new file (keep the same filename), or drop in a new file and update the `href` in `index.html`:

```html
<a class="cv-link" href="assets/cv.pdf" ...>CV</a>
```

### Change profile photo

Replace `assets/profile.jpg` with the new photo (keep the same filename), or drop in a new file and update the `src` in `index.html`:

```html
<img class="profile-photo" src="assets/your_photo.jpg" ... />
```

## Deploy

Push to `master`. GitHub Pages deploys automatically within ~1 minute.
