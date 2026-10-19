# DVN Flyer Generator

A static, mobile-friendly web app based on the current DVN flyer design. A user selects a photo, enters their name, previews the result, and downloads a PNG. It runs entirely in the browser; photos are not uploaded to a server.

## Files
- `index.html` — the generator UI and client-side canvas export.
- `template.svg` — the existing DVN flyer design used as the background.

## Test locally
Keep both files in the same folder and open `index.html` in a modern browser. If your browser blocks local SVG loading, use a local static server (for example, VS Code Live Server).

## Publish a public link with GitHub Pages
1. Sign in to GitHub and create a new **public** repository, for example `dvn-flyer-generator`.
2. Upload `index.html`, `template.svg`, and `README.md` to the repository root (not inside another folder).
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/(root)`, then save.
6. Wait for GitHub Pages to publish. The public link will look like `https://YOUR-USERNAME.github.io/dvn-flyer-generator/` (replace `YOUR-USERNAME` with your GitHub username). Copy the exact URL shown in Settings → Pages and share it in DVN.

## Notes
- No backend, account, or database is needed.
- The design is square 1254 × 1254 PNG, suitable for social posts.
- The photo is cropped to fit the portrait window. A future enhancement could add drag-to-position/zoom controls and configurable event details.
