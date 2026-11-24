# Airdrop Hunter 2.0 — installable starter edition

## What's included
- `index.html`: your existing tracker interface and browser-side logic
- `manifest.webmanifest`: app name, theme and install settings
- `sw.js`: basic offline caching
- `icon.svg`, `icon-192.png`, `icon-512.png`: app icons

## Test locally
Open `index.html` in a modern browser to test the tracker. Browser installation as a PWA
requires the files to be hosted over HTTPS (or served from localhost).

## Publish for phone installation
Upload the contents of this folder to a static HTTPS host such as GitHub Pages or Cloudflare Pages.
Then open the published HTTPS address in Chrome on Android and choose Install app / Add to Home Screen.

## Important limitations
This is an installable starter edition based on the supplied code. It still stores records
in the browser on one device. It does NOT yet discover live airdrops, connect to blockchains,
verify eligibility, monitor snapshots, fetch live prices, or claim tokens. Those require
trusted data sources and a backend/API integration. Never enter seed phrases or private keys.
