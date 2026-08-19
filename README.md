# Pixio Theme

**For personal use only.** This theme is intended exclusively for private, personal projects. Redistribution, resale, or public sharing of the files in this repository is not permitted.

## Overview

Pixio is a collection of static HTML templates and supporting assets (CSS, JavaScript, fonts, icons, images, and vendor libraries) for building personal web projects. Every page is a self-contained HTML file that can be opened directly in a browser or served from any static host.

## Project Structure

```
.
├── *.html          # Page templates (home, blog, shop, account, etc.)
├── css/            # Stylesheets (including skin color variants)
├── js/             # JavaScript files
├── fonts/          # Custom font files
├── icons/          # Icon assets
├── images/         # Image assets
└── vendor/         # Third-party libraries
```

## How to Import

1. **Clone or download** this repository into your local workspace.
2. **Place the folder** anywhere convenient on your machine.
3. Open any `.html` file directly in your browser, or serve the folder with a local server (for example):
   ```bash
   # Python 3
   python3 -m http.server 8000

   # Node.js (with http-server installed)
   npx http-server .
   ```
4. Visit `http://localhost:8000` (or whichever port your server uses) to browse the pages.

## How to Use

- **Pick a template:** Open any HTML file in the root folder (e.g. `index.html`, `about-us.html`, `blog-grid.html`, `product-detail.html`) — each one is a complete page layout.
- **Edit content:** Modify the HTML directly to change text, images, and links.
- **Adjust styling:** Edit files in the `css/` folder. Skin color variants are available in `css/skin/` — swap the skin stylesheet reference inside the page `<head>` to change the accent color.
- **Add behavior:** Update or extend the scripts in `js/` as needed for interactivity.
- **Replace assets:** Drop your own images into `images/`, icons into `icons/`, and fonts into `fonts/` while keeping the same file names, or update the references in the HTML/CSS accordingly.

## Notes

- All paths in the templates are relative, so the theme works from any directory or subdirectory.
- For best results, use a modern browser (latest Chrome, Firefox, Edge, or Safari).
- This theme is provided **as-is** for personal use only — no support, warranty, or updates are guaranteed.

---

*Personal use license — do not redistribute.*