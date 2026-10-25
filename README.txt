Budget Moth
=============
Open index.html in any modern browser to use it. Your data is saved in that browser.

To host it (needed for "Install app" on a phone):
1. Create a GitHub repository and upload every file in this folder to its root.
2. Settings > Pages > Deploy from a branch > main / (root).
3. Open https://<your-name>.github.io/<repo>/ and use Add to Home Screen / Install.

When you publish a new index.html, change VERSION in sw.js so installed copies refresh.
Keep all files together: index.html, manifest.webmanifest, sw.js, icon.svg, icon-192.png, icon-512.png, apple-touch-icon.png.

Sync between devices (Settings > Sync)
- Cloud sync: needs a GitHub token with only the "gist" permission and a passphrase you choose.
  Data is encrypted on your device before it is saved to a private gist. Use the same token and passphrase on each device.
- Sync file: Chrome or Edge on a computer can keep a file in iCloud Drive, Dropbox, OneDrive or Google Drive linked.
Both save and merge automatically. Cloud sync needs the https:// (GitHub Pages) address.

New in this version
- Month tab: "Where it went" donut and ranked list, by category or group, with change vs last month.
- Year tab: spending trend chart; pick categories, single category shows its budget as a dashed line. Tap points for values.
- Receipts: attach a photo on Add or when editing an entry. Photos stay on the device (not synced) and are included in Export backup (.json).
- Undo: header Undo button, Ctrl/Cmd+Z, and Settings > History and backup (undo back to here, redo).
- Backup reminder is now date-based (weekly by default; change in Settings). Not shown while syncing.
