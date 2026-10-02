# Life At NCC CIRS

A single-page photo gallery for NCC CIRS: platoons, parade classes, seva, events and more.

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `life-at-ncc-cirs`).
2. Upload everything in this folder (`index.html`, `README.md`, `.nojekyll`).
3. Go to **Settings → Pages**, set **Source** to *Deploy from a branch*, choose `main` and `/ (root)`, then Save.
4. After a minute your site is live at `https://<your-username>.github.io/life-at-ncc-cirs/`.

## Adding / removing photos
Tap **＋ Add photos** (bottom left) and enter the password to:
- add photos to a category, or create a new category;
- add a name and rank for each photo in platoon categories;
- remove photos (including original ones) and restore them later.

**Note:** on GitHub Pages, changes made through this panel are saved only in the browser you make them in. They are not shared with other visitors. To make permanent changes for everyone, edit `index.html` and re-upload it.

## Changing the password
The panel password lives in its own file, `config.js`. To change it on GitHub:
1. Open `config.js` in your repository and click the pencil (Edit) icon.
2. Change the text inside the quotes, e.g. `window.NCC_PASSWORD = "MyNewPassword";`
3. Click **Commit changes**. The site updates in a minute or so (refresh to see it).

`config.js` is a public file, so anyone who looks at it can read the password. Treat it as a casual guard, not real security.
