ARAB FX Trading Journal — updated PWA package

Files to upload to the ROOT of the existing GitHub repository:
- index.html
- manifest.webmanifest
- service-worker.js
- icon-192.png
- icon-512.png
- icon.svg
- README.txt

Upload all files at the repository root and commit the changes.
GitHub Pages will redeploy automatically.

The updated manifest includes the standard 192px and 512px PNG icons required by Chromium-based PWA install promotion. The page also includes an Install ARAB FX button; it can open the browser install prompt when Chrome provides it.

Important:
- This is a web app, not a native APK.
- Chrome decides whether and when to show its install option; a valid manifest cannot force the menu option to appear.
- Journal data stays in this browser/device unless manually exported. It is not uploaded to GitHub.
