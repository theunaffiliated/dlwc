# David L.W. Casimes — personal site

Static site, no build step. `index.html` (home), `experience.html`, `styles.css`.

## Publish on GitHub Pages
1. Create a new repository on GitHub (for a `username.github.io` URL, name it exactly `USERNAME.github.io`; any other name publishes at `USERNAME.github.io/REPO`).
2. Upload these three files (plus this README) to the repository root — "Add file → Upload files" works fine in the browser.
3. Settings → Pages → Build and deployment → Source: **Deploy from a branch** → Branch: `main` / `(root)` → Save.
4. Your site is live at the URL shown on that page within a minute or two.

To add a custom domain later, add a `CNAME` file containing the domain and point its DNS at GitHub Pages.
