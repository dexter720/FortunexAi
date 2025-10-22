# Fortunex PWA Pack

This folder contains:
- `icon-192.png` and `icon-512.png` (app icons)
- `manifest.json` (PWA manifest)
- `sw.js` (minimal service worker)
- `index.html` (example with manifest + SW registration)

## How to use with Vite (React)

1) Copy the files to your project:
   - Put `icon-192.png`, `icon-512.png`, `manifest.json`, and `sw.js` into your project's `public/` folder.
   - Replace your `index.html` with the one here **or** add the `<link rel="manifest"...>` and SW registration snippets manually.

2) Start dev:
   npm run dev

3) Deploy to Vercel/Netlify. Then add to Home Screen on mobile.

