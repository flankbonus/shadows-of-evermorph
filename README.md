# Shadows of Evermorph Score Keeper

Standalone responsive web/PWA version of the Evermorph score keeper.

## Files
- index.html — app
- manifest.json — installable PWA manifest
- sw.js — offline cache/service worker
- icon-192.png / icon-512.png — app icons

## Important
A PWA service worker requires the app to be served from HTTPS (or localhost). Opening index.html directly from the file system will run the tracker, but browser PWA installation/offline service-worker behavior will not be available.

The score is stored locally on the device/browser.
