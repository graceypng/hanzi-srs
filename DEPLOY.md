# Put 汉字 SRS on your phone (Netlify) — ~2 minutes

You have a folder called `hanzi-srs-pwa` containing `index.html`, `manifest.webmanifest`,
`sw.js`, and four `icon-*.png` files. Keep all of them together in that one folder.

## 1. Deploy to Netlify
1. Go to **https://app.netlify.com/drop**
2. Sign in (or create a free account — needed so the site stays up and keeps the same URL).
3. **Drag the whole `hanzi-srs-pwa` folder** onto the drop zone (drag the folder itself, not the files inside).
4. Netlify publishes it and gives you a URL like `https://gentle-otter-1234.netlify.app`.
5. (Optional) **Site configuration → Change site name** to make it memorable, e.g. `grace-hanzi.netlify.app`.

## 2. Install it on your phone
1. Open that URL on your phone **once while online** (so it caches for offline use).
2. **iPhone (Safari):** tap the Share button → **Add to Home Screen**.
   **Android (Chrome):** tap ⋮ → **Add to Home screen / Install app**.
3. Launch it from the new home-screen icon. It opens full-screen like a native app and works offline.

> Installing (Add to Home Screen) matters on iPhone: Safari can clear a *bookmarked* site's saved
> progress after ~7 days of no use, but an installed app is exempt. So install it, don't just bookmark.

## 3. Protect your progress
Your scheduling is saved on the phone itself (not on Netlify). As a backup, tap the **⇅** button in the
app now and then and **Export** a backup file (save it to Files or email it to yourself). If you ever
reinstall or switch phones, use **Import** to restore.

## 4. Getting an updated deck from me later
When I send you a newer folder (e.g. with more enriched cards):
- Open your site on Netlify → **Deploys** tab → drag the new folder in to publish an update.
- Same URL, and **your progress is untouched** (it lives on your phone, not in the deploy).
- Reopen the app while online once so it picks up the new version.

## Later: studying on a laptop too
This setup keeps progress on one device. When you want it synced across phone + laptop,
tell me and I'll add a small cloud-sync layer (a "sync code" you enter on each device).
