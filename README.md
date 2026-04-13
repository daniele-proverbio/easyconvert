# Currency Converter — PWA

A simple, offline-capable Progressive Web App for currency conversion.

## Features

- 📴 **Fully offline** — works without internet after first load
- 💾 **Persistent rate** — saved exchange rate loads automatically on next visit
- ⇄ **Swap currencies** — flip conversion direction with one tap
- 🆕 **New rate** — clear and re-enter a new rate at any time
- 📲 **Installable** — add to home screen on Android, iOS, and desktop

## Deploy to GitHub Pages

1. **Fork or upload** this folder to a new GitHub repository.

2. Go to **Settings → Pages** in your repository.

3. Under **Source**, choose:
   - Branch: `main` (or `master`)
   - Folder: `/ (root)`

4. Click **Save**. Your app will be live at:
   ```
   https://<your-username>.github.io/<repo-name>/
   ```

5. That's it! Share the URL — users can open it in any browser and install it as an app.

## File structure

```
├── index.html      ← Main app (single file)
├── sw.js           ← Service Worker (offline caching)
├── manifest.json   ← PWA manifest
├── icons/
│   ├── icon-192.png
│   └── icon-512.png
└── README.md
```

## How to use

1. On first open, enter your two currency codes (e.g. `USD`, `EUR`) and the exchange rate.
2. Tap **Save rate & start**.
3. Enter an amount and tap **Convert**.
4. Use ⇄ to swap currencies, or **New** to update the rate.

## Notes

- Exchange rates are entered manually — the app does not fetch live rates.
- All data is stored in `localStorage` on the user's device.

---

Developed by Daniele Proverbio, 2026
