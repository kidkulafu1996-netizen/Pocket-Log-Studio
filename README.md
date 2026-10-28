# Pocket Log Studio

Cut and colour grade DJI Osmo Pocket D-Log 10-bit footage on your phone. Import, apply and make `.cube` LUTs. Everything runs on the device; footage is never uploaded.

## Put it online with GitHub Pages

1. Create a new public repository, for example `log-studio`.
2. Upload every file in this folder, keeping the `icons` folder.
3. Go to **Settings → Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
4. After a minute the app is live at `https://<your-username>.github.io/log-studio/`.

## Install on your phone

Send yourself this link and tap it: `https://<your-username>.github.io/log-studio/install.html`

- **iPhone (Safari):** open the link, tap **Share**, then **Add to Home Screen**.
- **Android (Chrome):** open the link and tap **Install** in the app, or menu **⋮ → Install app**.

Open it once while online. After that it opens offline from the home screen.

## Updating

Replace `index.html` in the repo. To force phones to pick up a change right away, also bump `VERSION` in `sw.js` (for example `pls-v2`).
