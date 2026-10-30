# ARAB FX Trading Journal app

This is an installable Progressive Web App (PWA), not a native Android APK.

## Publish it
1. Upload the contents of this folder to a static website host that provides HTTPS (for example, a GitHub Pages or Netlify site).
2. Open the published HTTPS website in Chrome on Android.
3. Use Chrome's menu and choose **Install app** or **Add to Home screen**. If the page shows an Install app button, you can use that too.

## Data and privacy
- Trade entries are stored in browser local storage on that device.
- There is no account, cloud sync, broker connection, or automatic backup.
- Use **Export CSV** regularly to back up your journal.
- Clearing browser site data may remove saved journal entries.

## Files
- `index.html`: trading journal
- `manifest.webmanifest`: app identity and display settings
- `service-worker.js`: offline caching
- `icon.svg`: app icon
