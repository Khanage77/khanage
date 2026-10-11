# Khanage Workout Tracker

A phone-first workout logger: two sets per exercise by default — set 3, 4 or 5 under Settings, or tap **+ set** on any exercise. Installs as an app, works offline, data stays on your device.

## Deploy on GitHub Pages (free)

1. Create a new public repository on GitHub, e.g. `khanage`.
2. Upload every file in this folder (keep the `icons/` folder as is).
3. In the repo: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save**.
4. After a minute the app is live at `https://<your-username>.github.io/khanage/`.

## Install on Android (Galaxy S25 Ultra)

1. Open the link above in **Chrome**.
2. Tap **Install** in the app header (or Chrome menu ⋮ → **Add to Home screen** → **Install**).
3. Open **Khanage** from the home screen. It works without signal.

## Your data

- Stored in the phone's browser storage, not in the cloud.
- **Backup** saves a `.json` file; **Restore** loads it on a new phone. **Export CSV** gives a spreadsheet of every set.
- Uninstalling the app or clearing Chrome's site data deletes the workouts — take a backup first.

## Updating the app

Edit the files, bump `CACHE` in `sw.js` (e.g. `khanage-v2`), and push. Phones pick up the new version on their next open.
