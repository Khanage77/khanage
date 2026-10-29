# YouFit Workout Tracker

A phone-first workout logger: two sets per exercise by default — set 3, 4 or 5 under Settings, or tap **+ set** on any exercise. Installs as an app, works offline, data stays on your device.

- **Repeat last** starts a new workout with the same exercises and set counts as your previous one; last time's reps and weights show faintly in each box so you can match or beat them.
- **kg / lb** is remembered per workout. Tapping the toggle converts the open workout and becomes the default for new ones; older workouts keep the unit they were logged in.
- **Personal records**: when a set beats your best ever weight (or reps, for bodyweight moves) for that exercise, you get a "New PR!" cheer, the set turns green, and it is starred in History.
- When a new version is published, the app shows a **Reload** prompt instead of silently waiting for the next open.

## Deploy on GitHub Pages (free)

1. The repository is `khanage` under the `khanage77` account, so the address stays `https://khanage77.github.io/khanage/`. Renaming the repository would change the address and break the app already installed on phones.
2. Upload every file in this folder (keep the `icons/` folder as is), replacing the old ones.
3. **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: main / (root) → Save** (only needed the first time).
4. After a minute the app is live.

## Install on Android (Galaxy S25 Ultra)

1. Open the link above in **Chrome**.
2. Tap **Install** in the app header (or Chrome menu ⋮ → **Add to Home screen** → **Install**).
3. Open **YouFit** from the home screen. It works without signal.

## Your data

- Stored in the phone's browser storage, not in the cloud.
- **Backup** saves a `.json` file; **Restore** loads it on a new phone (backups from the Khanage days still restore). **Export CSV** gives a spreadsheet of every set.
- Uninstalling the app or clearing Chrome's site data deletes the workouts — take a backup first.

## Updating the app

Edit the files, bump `CACHE` in `sw.js` (e.g. `youfit-v5`), and push. Phones that already have the app show a Reload prompt the next time it is opened or brought to the front.
