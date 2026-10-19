# Sajan K.C. research website (static HTML)

A simple, free GitHub Pages website. No Hugo, no build step.

## Personalize
- Replace `images/headshot-placeholder.svg` with your photo in `images/headshot.jpg`; then change the image `src` in `index.html` to `images/headshot.jpg` and its `alt` to `Portrait of Sajan K.C.`. Square or 4:5 crops work well.
- Add your real CV to `assets/Sajan_KC_CV.pdf`. Remove the line `document.getElementById('cv-link').hidden = true;` from `script.js` to show the CV link.
- Replace the Selected Publications placeholder with verified publication entries from your CV.
- Adjust the accent in `style.css` via `--red:#941f35`.

## Safe test deployment
1. Create a **new public repository** under your GitHub account, e.g. `research-site-preview` (do not overwrite `Sajan-KC.github.io` yet).
2. Upload the contents of this folder to the **root** of that repository (`index.html` must appear at the root).
3. In Settings > Pages select **Deploy from a branch**, branch **main**, folder **/(root)**, then save.
4. Preview at `https://sajan-kc.github.io/research-site-preview/`.
5. Once satisfied, replace the old Hugo Blox site in `Sajan-KC.github.io` with these static files (backup/archive Hugo files first) and set Pages to deploy from main/root.

## Note
Google Fonts uses an external CDN; the page falls back to Arial if unavailable. All required site source files are included locally.
