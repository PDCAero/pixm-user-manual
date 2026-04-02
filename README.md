# PIXM User Manual

Documentation site built with [Docsify](https://docsify.js.org/) and hosted on GitHub Pages.

**Live site:** https://PDCAero.github.io/pixm-user-manual/

---

## Editing content

All documentation lives in the `docs/` folder as plain Markdown (`.md`) files.

### To edit an existing page
1. Find the `.md` file in `docs/`
2. Click the pencil ✏️ icon on GitHub (or edit locally and push)
3. The live site updates immediately — no build step

### To add a new page
1. Create a new `.md` file in the appropriate subfolder under `docs/`
2. Open `docs/_sidebar.md` and add one line:
   ```
     - [Page Title](path/to/your-file.md)
   ```
3. Commit and push

### Key files

| File | What it controls |
|---|---|
| `docs/_sidebar.md` | Left-hand navigation |
| `docs/_navbar.md` | Top navigation bar |
| `docs/home.md` | Home page content |
| `docs/assets/css/theme-custom.css` | Visual theme / colours |
| `docs/index.html` | Docsify config (rarely needs touching) |
