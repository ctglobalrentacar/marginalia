# Marginalia

A mobile-first book tracker in Spanish and English. Log pages, keep a library, see your reading journal, goals and stats.

It is a static site (no build step). Each person's library, cover photos, profile photo and background are saved in their own browser, so nothing is shared or synced between devices.

## Files

- `index.html` is the whole app
- `manifest.webmanifest`, `icon-192.png`, `icon-512.png` let phones add it to the home screen

## Online book data

Search in Explore and automatic covers use the public Google Books and Open Library APIs, called from the visitor's browser. Only the title and author being looked up are sent. If those services are unreachable, the app still works and uses generated covers.

## Publish with GitHub Pages

Settings → Pages → Build and deployment → Deploy from a branch → `main` / `(root)` → Save.
