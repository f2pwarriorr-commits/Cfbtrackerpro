GRIDIRON STATS CENTER — PWA

Files:
- index.html              Main app
- manifest.webmanifest    Installable PWA metadata
- service-worker.js       Offline caching
- icon-192.png            Android/app icon
- icon-512.png            Android/app icon

DEPLOYMENT:
1. Upload all five files to the root of a GitHub repository.
2. GitHub: Settings -> Pages.
3. Source: Deploy from a branch.
4. Branch: main, folder: / (root).
5. Open the generated HTTPS GitHub Pages URL on Android Chrome.
6. Chrome menu -> Install app (or Add to Home screen).

IMPORTANT:
The app stores its working database in browser localStorage. Use the built-in Export button to back up your data before clearing browser data or changing devices.
