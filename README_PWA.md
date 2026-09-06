# Nyao Scalper PWA

Mobile-first Nyao Scalper live-signal web app, ready to install as a PWA on Android/Chrome and supported browsers.

## Files
- `index_connected.html` — live dashboard
- `manifest.webmanifest` — PWA app metadata
- `sw.js` — service worker/offline app shell
- `icons/` — 192px/512px app icons

## Deploy
1. Upload all files/folders to the same Vercel project.
2. Keep `index_connected.html` as the deployed page, or rename it to `index.html` if you want the root URL to open directly.
3. The site must be served over HTTPS for PWA installation/service worker support.

## Supabase
Replace `SUPABASE_URL` and `SUPABASE_ANON_KEY` in `index_connected.html`. Never put the EA device token in this browser file.

## Install
- Android Chrome: open the site, then use the browser Install/Add to Home screen option, or use the in-page Install button when Chrome exposes it.
- iPhone/iPad Safari: Share → Add to Home Screen.
- Desktop Chrome/Edge: use the install icon in the address bar when available.
