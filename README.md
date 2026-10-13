# The E-Street Café website (demo)

A multi-page static site: Home, Menu, Order, Track, Gallery, About, Visit and Account. Plain HTML, CSS and JavaScript, so no build step.

## Host on GitHub Pages
1. Create a new public repository on GitHub.
2. Upload everything in this folder to the repository root (keep `index.html` at the top level).
3. Go to **Settings > Pages**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then Save.
4. After a minute the site is live at `https://YOUR-USERNAME.github.io/REPO-NAME/`.

## Before you send it to the café
- Confirm the phone number and opening hours (Visit page, `js/app.js`), and the prices (`M` array in `js/app.js`, taken from their Feb 2022 menu).
- Photos in `img/` come from the café's Instagram. Get their permission or use your own shots before sharing publicly.
- Login, orders, the map and live tracking are a front-end demo only. Data stays in the visitor's browser. A real version needs a backend, payments and a map service.
