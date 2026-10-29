MY WEALTH TRACKER — iPhone web app

Files:
- index.html: app
- manifest.webmanifest: home-screen app metadata
- sw.js: offline cache service worker

IMPORTANT:
This app stores data in the browser's localStorage on the device. It does not sync to iCloud and does not connect to banks or brokers. Export JSON backups regularly.

To install as a true Home Screen web app:
1. Host these files on an HTTPS static host (for example, a private GitHub Pages site or another static hosting service).
2. Open the HTTPS URL in Safari on the iPhone.
3. Tap Share > Add to Home Screen.
4. Open the app from the new Home Screen icon.

Opening index.html directly from Files is useful for a quick preview, but service-worker/offline and installable PWA behavior require HTTPS hosting.

Opening data:
- Savings starts at ₹2,60,000 based on the amount supplied earlier.
- MF and stocks start at ₹0 as placeholders; replace them with actual current market values.
- Targets: savings ₹20L, mutual funds ₹20L, stocks ₹2L.
- Horizon: 24 months.
