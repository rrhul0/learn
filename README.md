# Multiplication Practice

A mobile-first math practice PWA with an on-screen keypad, fully installable and offline-capable.

## Modes
- Multiplication
- Square / Square Root
- Cube / Cube Root
- Pythagorean Triplets (fill in the missing number)
- Fraction ↔ Percentage

## Features
- Adaptive question picker: facts you get wrong (or reveal) come up more often; never repeats the same question back-to-back
- Optional auto-submit once the answer has enough digits, or use the Submit button
- Reveal-answer button
- Settings modal (number ranges, fraction options, auto-submit toggle)
- Installable as a PWA with offline support via a service worker

## Deploying
This is a static site — no build step. Deploy the contents of this folder as-is to:
- **Vercel**: `vercel --prod` from this folder, or drag-and-drop at vercel.com/new
- **GitHub Pages**: Settings → Pages → deploy from this branch/folder
- **Netlify**: drag the folder onto app.netlify.com/drop

Files:
- `index.html` — the app
- `manifest.json` — PWA manifest
- `sw.js` — service worker (offline caching)
- `icon-192.png`, `icon-512.png` — app icons
