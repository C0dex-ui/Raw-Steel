# Hercules Raw Steel Page

Static / Elementor-ready page for Hercules raw steel (`/raw-steel/`).

## Deploy on Vercel

1. Import this GitHub repo in Vercel: https://github.com/C0dex-ui/Raw-Steel
2. Framework Preset: **Other** (static)
3. Build Command: leave **empty**
4. Output Directory: leave **empty** (or `.`)
5. Deploy

Root URL (`/`) serves `index.html`. `/raw-steel` also works.

## Local preview

```bash
npx serve -l 3000 .
# http://127.0.0.1:3000/
# http://127.0.0.1:3000/raw-steel.html
```

## Files

| File | Purpose |
|------|---------|
| `index.html` | **Vercel / static hosting** entry (full HTML document) |
| `raw-steel.html` | Elementor fragment (no html/body wrapper) |
| `raw-steel.css` | Scoped styles under `.hc-raw-steel` |
| `raw-steel-paste.html` | One-file Elementor paste (CSS inlined) |
| `img/rawl-steel/` | Hero + product images |
| `vercel.json` | Routes for `/raw-steel` |

## Elementor (WordPress)

Use `raw-steel-paste.html` in an HTML widget with Page Layout = Elementor Full Width.