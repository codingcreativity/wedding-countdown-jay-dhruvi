# Jay & Dhruvi Wedding Countdown

Live countdown to 29 January 2027, 12:00 noon IST, Rajkot, Gujarat.
Installable as an app (PWA) and works offline after the first visit.

Live site: https://codingcreativity.github.io/wedding-countdown-jay-dhruvi/

## Files

| File | What it does |
| --- | --- |
| `index.html` | The whole website (design, countdown, animations) |
| `manifest.webmanifest` | App name, colours and icons used when installed |
| `sw.js` | Service worker: saves the site so it opens offline |
| `icons/` | App icons (192, 512, maskable, Apple touch, favicon) |

## Deploy on GitHub Pages

1. Put all of these files at the root of the repository (`index.html` must be at the top level).
2. Repository **Settings > Pages > Build and deployment**: source **Deploy from a branch**, branch **main**, folder **/ (root)**.
3. Wait a minute, then open the live site address above.

## Install as an app

- **Android / Chrome / Edge:** tap the **Install app** button in the top bar, or the install icon in the address bar.
- **iPhone / iPad (Safari):** Share button, then **Add to Home Screen**.

## Updating the site

Every time you change any file, open `sw.js` and bump `VERSION` (for example `v1` to `v2`).
Without that, phones that already installed the app may keep showing the old saved copy.

## Changing details

All text lives in `index.html`: names, venue, story chapters and the footer credit.
The countdown target is the `TARGET` line near the bottom of the script.
The calendar link and the page meta description also mention the date and venue.

Developed by [Dvij Technology](https://dvijtechnology.com/)
