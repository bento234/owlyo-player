# GitHub Pages Dateien

Dieser Ordner enthaelt eine einfache statische Website fuer die rechtlichen Seiten von `KidsCastPlayer`.

## Inhalt

- `index.html` - Startseite mit Links
- `datenschutz.html` - Datenschutzerklaerung
- `impressum.html` - Impressum
- `styles.css` - gemeinsames Styling
- `404.html` - Fallback/Weiterleitung
- `.nojekyll` - deaktiviert Jekyll-Verarbeitung auf GitHub Pages

## Vor dem Deployment

1. Platzhalter ersetzen:
   - `[VORNAME NACHNAME]`
   - `[STRASSE, HAUSNUMMER, PLZ ORT, LAND]`
   - `[SUPPORT-E-MAIL]`
2. Lokal testen, indem `index.html` im Browser geoeffnet wird.

## Deployment-Hinweis

Wenn du GitHub Pages direkt aus dem Repository ohne Build-Workflow hosten willst, liegt die Quelle in GitHub typischerweise im Root (`/`) oder in `/docs`. Falls du diesen Unterordner direkt deployen willst, empfiehlt sich ein kurzer GitHub-Action-Deploy-Workflow.
