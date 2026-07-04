# Bill Tracker PWA

A standalone bill tracker app. All data is saved locally on your device (localStorage) — no account, no server, works offline.

## Files
- `index.html` — the entire app
- `manifest.json` — makes it installable as an app
- `sw.js` — service worker for offline use
- `icon-192.png`, `icon-512.png` — app icons

## Host it free on GitHub Pages (10 minutes)

1. Go to github.com and sign in (create a free account if needed)
2. Click **+** (top right) → **New repository**
   - Name it something like `bills`
   - Set it to **Public** (required for free Pages)
   - Click **Create repository**
3. Click **uploading an existing file** on the new repo page
4. Drag in all 5 files from this folder → **Commit changes**
5. Go to **Settings** → **Pages** (left sidebar)
   - Under "Branch", select **main** and **/ (root)** → **Save**
6. Wait ~1 minute. Your app is live at:
   `https://YOURUSERNAME.github.io/bills/`

## Install on your Android phone

1. Open that URL in **Chrome**
2. Chrome menu (⋮) → **Add to Home screen** → **Install**
3. It installs as a standalone app: own icon, full screen, no browser bar, works offline

## Notes

- Data lives only on your phone. Clearing Chrome's site data will erase it, so avoid "Clear browsing data" for this site.
- To update the app later, just replace `index.html` in the repo. Bump the cache name in `sw.js` (e.g. `bills-v2`) so phones pick up the new version.
- The repo being public means the *code* is public — but your bill data never leaves your phone.
