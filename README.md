# Pasaporte A1 — PWA release

Upload all files and folders in this directory to the root of your GitHub Pages repository.

Required files:
- index.html
- manifest.webmanifest
- service-worker.js
- icons/icon-192.png
- icons/icon-512.png

After uploading, open your GitHub Pages URL. The browser can then install the game as a PWA and cache it for offline use.

Notes:
- Audio uses the browser's built-in Web Speech API with a Spanish voice when available.
- Progress is stored locally in the browser via localStorage. No account and no server are used.
- Service workers work only via HTTPS or localhost. GitHub Pages uses HTTPS, so offline caching works there.


## Testrapport

Open `test-report.html` via dezelfde GitHub Pages-site om de echte woorddata, PWA-bestanden en basislogica automatisch te controleren.
