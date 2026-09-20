LingoRSR — Free GitHub Pages Setup

1. Create/sign in to a free GitHub account.
2. Create a new PUBLIC repository named: LingoRSR
3. Choose "uploading an existing file".
4. Upload ALL of these files to the repository root:
   index.html
   manifest.webmanifest
   sw.js
   icon-192.png
   icon-512.png
5. Commit the files.
6. Open repository Settings > Pages.
7. Under Build and deployment, choose:
   Source: Deploy from a branch
   Branch: main
   Folder: /(root)
8. Save. GitHub will show the live Pages address when deployment finishes.
9. Open that address in Safari on iPhone.
10. Tap Share > Add to Home Screen > Add.

Important:
- Keep the same website address. Browser study progress is stored locally and is tied to the site's origin.
- Clearing Safari/site data can erase local progress.
- The included service worker caches the app for offline use after it has loaded successfully.
