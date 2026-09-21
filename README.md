# YEC Management — website

Static multi-page site (plain HTML/CSS/JS). Host anywhere, including **GitHub Pages**.

## Files
- `index.html`, `about.html`, `what-we-do.html`, `clients.html`, `credentials.html`, `social-value.html`, `careers.html`, `contact.html`
- `assets/css/styles.css` — all styling
- `assets/js/main.js` — navigation, expanding panels, company-profile PDF
- `assets/img/` — photography, logo and favicon

## Deploy to GitHub Pages
1. Create a repository and upload the contents of this folder (keep the folder structure).
2. Repo **Settings → Pages → Build and deployment**: Source = *Deploy from a branch*, Branch = `main` (root).
3. Your site publishes at `https://<username>.github.io/<repo>/`.

The included `.nojekyll` file makes sure the `assets/` folder is served as-is.

## Edit content
Text lives directly in each `.html` file. The six services, the client list and the
credentials are generated from arrays at the top of `assets/js/main.js` — edit them there
to update every page at once.

© 2026 YEC Management Ltd.
