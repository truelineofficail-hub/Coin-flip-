GUESS – heads or tails (installable, fully offline)

Files
  index.html     the whole game (images built in, no internet needed)
  manifest.json  app name "Guess", black theme, icons
  sw.js          service worker: caches everything for offline use
  icons/         app icons

Install (needs the folder hosted over HTTPS, e.g. Netlify, Vercel, GitHub Pages, Cloudflare Pages)
  1. Upload the whole "guess" folder and open the link once while online.
  2. Android / Chrome / Edge: tap the INSTALL button in the app (or browser menu > Install app).
  3. iPhone / iPad (Safari): Share > Add to Home Screen.
  After the first visit the app opens and plays with no internet.

Updating: change VERSION in sw.js (guess-v2 -> guess-v3) whenever you edit the files.
Note: opening index.html straight from the files still plays offline, but installing needs HTTPS.
