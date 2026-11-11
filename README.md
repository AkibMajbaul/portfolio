# Majbaul Hossain Bhuiyan — Portfolio

Personal portfolio website: a single, self-contained `index.html` (no build step, no dependencies).
Images are embedded in the file; only the Google Fonts stylesheet is loaded from the web.

## Sections
About · Experience · Education · Skills & Certifications (with verification links) · Connect

## Run locally
Open `index.html` in any browser.

## Deploy with GitHub Pages
1. Create a new repository (for a user site, name it `<your-username>.github.io`).
2. Upload `index.html`, `.nojekyll` and `README.md` to the repository root.
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then **Save**.
4. After a minute the site is live at `https://<your-username>.github.io/` (or `/<repo-name>/` for a project site).

## Editing
Everything lives in `index.html`: text in the HTML, colors in the `:root` CSS variables (`--accent` is the indigo theme color).
