# Fokexa

Offline-first time tracker and productivity app for students.

## What It Does

- Study timer and manual session logging
- Subject, chapter, and subtopic tracking
- Session log and analytics
- Day / week / month sticky-note To Do board
- Calendar and countdowns
- Backup, restore, and auto-backup
- Theme, font, and font color customization
- Windows desktop app wrapper with Electron

## Privacy

Fokexa is offline-first. User data is stored locally on the user's device unless they export a backup or enable future optional sync features.

## Roadmap

- `v1.0`: Offline-first public launch
- `v1.1.x`: Small fixes, polish, and quality-of-life updates over 3-6 months
- `v2.0`: Optional cloud sync while keeping offline mode available

## Run Locally

Open `index.html` in a browser.

For the Windows desktop wrapper:

```powershell
npm install
npm run build
```

The installer is generated in `dist/`.

## GitHub Pages

For a simple website upload, publish:

- `index.html`
- `assets/`
- `README.md`
- `CHANGELOG.md`

Do not upload `node_modules/` or `dist/`.
