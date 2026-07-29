# Hercules Raw Steel Page

Elementor-ready full-width page content for `/raw-steel/` on [corrugated-industries.com](https://corrugated-industries.com/).

## Files

| File | Purpose |
|------|---------|
| `raw-steel.html` | Page markup (preview + base for edits) |
| `raw-steel.css` | Scoped styles under `.hc-raw-steel` |
| `raw-steel-paste.html` | **Paste this into Elementor** (CSS inlined) |
| `img/rawl-steel/` | Hero graphic + product photos |

## Local preview

```bash
npx serve -l 3000 .
# open http://127.0.0.1:3000/raw-steel.html
```

## Elementor setup

1. Page Settings → **Page Layout: Elementor Full Width**
2. Hide Title = Yes
3. One section: Full Width, Stretch Section On, padding 0, no gap
4. Column: 100% width, padding 0
5. HTML widget → paste entire contents of `raw-steel-paste.html`
6. Upload images from `img/rawl-steel/` to Media Library and update image paths to full WP URLs

## Products

- I-Beams
- Angle Iron
- Flat Bar
- Flat Plate
