# Majbaul Hossain Bhuiyan — Portfolio

Personal portfolio website built with plain HTML, CSS and a little JavaScript (no build step, no dependencies).
Only the Google Fonts stylesheet is loaded from the web.

## Project structure
```
index.html          the whole site (text, styles, scripts)
assets/images/      profile photo, avatar, Gmail logo and certificate images
.nojekyll           tells GitHub Pages to serve files as-is
```

## Sections
About · Experience · Education · Skills & Certifications (with verification links) · Connect

## Run locally
Open `index.html` in a browser. Keep the `assets/images/` folder next to it, otherwise the images will not show.

## Deploy with GitHub Pages
1. Create a repository (for a user site, name it `<your-username>.github.io`).
2. Upload everything in this folder, keeping the `assets/images/` folder structure.
3. **Settings → Pages → Source:** *Deploy from a branch* → `main` and `/ (root)` → **Save**.
4. The site goes live at `https://<your-username>.github.io/` after a minute or two.

## Common edits
- **Add a certificate:** put the image in `assets/images/`, then copy an existing `<article class="card cert">` block in `index.html` and change the image name, title, issuer, date and Verify link.
- **Change the photo:** replace `assets/images/profile.jpg` (square, about 560×560) and `avatar.jpg` (about 112×112) keeping the same file names.
- **Change the theme color:** edit `--accent` in the `:root` CSS variables (indigo `#4f46e5`).
