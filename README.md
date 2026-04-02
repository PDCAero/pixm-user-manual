# My Docs

Documentation site built with [Docsify](https://docsify.js.org/) and hosted on GitHub Pages.

**Live site:** https://YOUR-ORG.github.io/YOUR-REPO/

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

---

## Local preview

No install required — just serve the `docs/` folder:

```bash
# Python (built into macOS/Linux)
cd docs && python3 -m http.server 3000

# Node (if you have npx)
npx serve docs
```

Then open http://localhost:3000

---

## GitHub Pages setup

1. Go to **Settings → Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / folder: `/docs`
4. Save
