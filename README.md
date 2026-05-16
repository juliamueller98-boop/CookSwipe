# CookSwipe

Eine private Rezepte-Swipe-App. Live unter `https://USERNAME.github.io/REPONAME/` nach Deployment.

## Dateien

| Datei | Zweck |
|---|---|
| `index.html` | Die App |
| `manifest.json` | PWA-Metadaten |
| `service-worker.js` | Offline-Cache und Update-Strategie |
| `robots.txt` | Sperrt Suchmaschinen-Indexierung |
| `rezepte-cookswipe.csv` | Initialer Rezeptbestand (Fallback ohne Sheet) |
| `images/` | Bilder und Icons |

## Datenschutz und Auffindbarkeit

- Suchmaschinen-Sperre über `<meta name="robots" content="noindex">` und `robots.txt`
- Schriftarten über Bunny Fonts (DSGVO-konform, EU-gehostet)
- Kein Backend, keine Cookies, kein Tracking
- localStorage nur für "heute schon gewischt"-Liste (täglicher Reset)

## Setup

Siehe `ANLEITUNG-CookSwipe.md` für die Schritt-für-Schritt-Anleitung.
