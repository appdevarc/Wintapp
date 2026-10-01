# ❄️ Winter Arc — Installable PWA

## Fastest free setup: GitHub Pages

1. Create a new GitHub repository, e.g. `winter-arc`.
2. Upload ALL 4 files from this folder:
   - `index.html`
   - `manifest.webmanifest`
   - `sw.js`
   - `icon.svg`
3. In GitHub: **Settings → Pages**
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main** / root
5. Wait for GitHub Pages to publish the site.
6. Open the published `https://...github.io/winter-arc/` address in Chrome on your phone.
7. Chrome should show **Install app** / **Add to Home screen**.
8. Install it. Open it from your home screen like a normal app.

The tracker stores daily ticks and notes in the browser's local storage and the PWA caches the app for offline use.

IMPORTANT:
- Keep using the same installed app/browser profile so your local progress remains available.
- Do not clear Chrome site data for the app unless you have a backup.
