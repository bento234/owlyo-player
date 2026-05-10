# GitHub Pages Dateien

Dieser Ordner enthaelt eine einfache statische Website fuer die rechtlichen Seiten von `Owlyo Podcast Player`.

## Inhalt

- `index.html` - Startseite mit Links
- `index-en.html` - English start page with links
- `datenschutz.html` - Datenschutzerklaerung
- `privacy-policy.html` - Privacy Policy (English)
- `impressum.html` - Impressum
- `legal-notice.html` - Legal Notice / Imprint (English)
- `styles.css` - gemeinsames Styling
- `404.html` - Fallback/Weiterleitung
- `.nojekyll` - deaktiviert Jekyll-Verarbeitung auf GitHub Pages

## Vor dem Deployment

1. Platzhalter ersetzen:
   - `Benjamin Jürgens`
   - `Postfach folgt`
   - `owlyo-support@bendreality.de`
2. Lokal testen, indem `index.html` im Browser geoeffnet wird.

## Deployment-Hinweis

Wenn du GitHub Pages direkt aus dem Repository ohne Build-Workflow hosten willst, liegt die Quelle in GitHub typischerweise im Root (`/`) oder in `/docs`. Falls du diesen Unterordner direkt deployen willst, empfiehlt sich ein kurzer GitHub-Action-Deploy-Workflow.
