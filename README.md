# Mulero Repair Onepager

Statische Onepager-Webseite für den Reparaturservice **Mulero Repair** in Sprockhövel.

## Lokal öffnen

Die Seite benötigt kein Backend und keine Datenbank.

1. Öffne `index.html` direkt im Browser.
2. Prüfe die Seiten `impressum.html` und `datenschutz.html`.
3. Prüfe vor Veröffentlichung Impressum, Datenschutz und die finale Domain.

## Kontakt- und Profil-Links

- WhatsApp: `https://wa.me/4915730198873?text=Hallo%20Mulero%20Repair%2C%20ich%20habe%20einen%20PS5%20Controller%20mit%20Stickdrift`
- eBay: `https://www.ebay.de/usr/mulero-repair`
- Kleinanzeigen: `https://www.kleinanzeigen.de/pro/mulero-athletic-goods`

## Vor Veröffentlichung prüfen

- Optional nach Deployment die finale Domain in den strukturierten Daten von `index.html` ergänzen.
- Optional das Hero-Bild in `assets/hero-repair-workbench.webp` und `assets/hero-repair-workbench.png` austauschen.

## Deployment auf GitHub Pages

1. Neues GitHub-Repository erstellen.
2. Alle Dateien hochladen oder per Git pushen.
3. In GitHub unter `Settings > Pages` die Quelle `Deploy from a branch` auswählen.
4. Branch `main` und Ordner `/root` auswählen.
5. Die veröffentlichte URL in den strukturierten Daten in `index.html` eintragen.

## Deployment auf Vercel

1. Projekt bei Vercel importieren.
2. Als Framework `Other` beziehungsweise statisches Projekt verwenden.
3. Kein Build Command nötig.
4. Output Directory leer lassen oder auf das Projektverzeichnis zeigen lassen.
5. Nach dem Deployment die echte Domain in `index.html` eintragen.

## Dateien

- `index.html` - SEO-Onepager
- `styles.css` - responsive Styling
- `impressum.html` - Impressum
- `datenschutz.html` - Datenschutzerklärung
- `assets/hero-repair-workbench.webp` - optimiertes Hero-Bild
- `assets/hero-repair-workbench.png` - Fallback-Hero-Bild
