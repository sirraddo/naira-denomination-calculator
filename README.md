# Naira Denomination Calculator

A simple, installable web app for counting Nigerian cash and breaking down amounts into notes/coins.

## Features
- **Count Cash tab** — enter how many of each note/coin you have (₦1000 down to ₦1), get an instant total. Great for reconciling POS/agent cash.
- **Breakdown tab** — enter any amount, get the fewest notes/coins needed to make it up.
- **Installable** — works as a Progressive Web App (PWA), so it can be added to your phone's home screen or installed on your laptop like a native app, and works offline after first load.

## Files
- `index.html` — the app (HTML, CSS, JS all in one file)
- `manifest.json` — PWA manifest (app name, icons, colors)
- `sw.js` — service worker (enables offline use)
- `icon.svg`, `icon-192.png`, `icon-512.png` — app icons

## Running locally
Just open `index.html` in any browser — no server needed for basic use.
For full offline install support, host it (e.g. GitHub Pages) since service workers require http/https, not `file://`.
