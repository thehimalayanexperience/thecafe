repo: thehimalayanexperience/thecafe
branch: main

## Last sync

date: 2026-09-09T00:00:00Z

### Updated in this project

- Repository was empty; the whole site was authored here, ready to push.
- Menu moved out of hardcoded HTML into `data/menu.json` as the single source of truth.
- Added a staff admin panel that publishes `data/menu.json` back to this repo via the GitHub Contents API.
- Added a self-contained QR encoder and printable table/counter QR cards.
- Mobile-first header and ordering for the QR path; admin renamed to adminpanelthecafe.dc.html; real cafe photos wired into the menu data.

## Screen map

| Project screen | Repo files |
| --- | --- |
| index.dc.html | (new) index.dc.html, data/menu.json, assets/logo.png |
| adminpanelthecafe.dc.html | (new) adminpanelthecafe.dc.html, data/menu.json |
| qr-cards.dc.html | (new) qr-cards.dc.html, qr.js, doc-page.js |
| Direction-A-Paper.dc.html | (design exploration, not for the repo) |
| Direction-B-Dusk.dc.html | (design exploration, not for the repo) |
