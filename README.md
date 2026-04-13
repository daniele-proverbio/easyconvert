# EasyConvert Currency Converter — PWA

A simple, offline-capable Progressive Web App for currency conversion.

## Features

- **Fully offline** — works without internet after first load
- **Persistent rate** — saved exchange rate loads automatically on next visit
- **Swap currencies** — flip conversion direction with one tap
- **New rate** — clear and re-enter a new rate at any time
- **Installable** — add to home screen on Android, iOS, and desktop

## Access and Install
Go to daniele-proverbio.github.io/easyconvert and Install on your home screen. Look up for "Info" for installation instructions. 

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
