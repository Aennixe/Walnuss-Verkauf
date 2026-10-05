# Walnuss-Verkauf – iPhone Offline-App

Die App ist als kleine lokale Web-App/PWA gedacht.

## Funktionen
- Bestellungen mit Name, Kontakt, Menge, Preis/kg, Abholung/Lieferung, Termin und Notiz
- automatische Gesamtpreisberechnung
- Gesamtbestand / reserviert / verfügbar
- Bestandsänderungen
- Status: Offen / Erledigt / Storniert
- lokale Speicherung im Browser
- JSON-Backup und Wiederherstellung
- keine Anmeldung und kein Server

## Wichtiger iPhone-Hinweis
Eine iPhone-Web-App lässt sich nicht zuverlässig direkt aus einer lokalen HTML-Datei als Home-Bildschirm-App installieren, weil Safari für installierbare Web-Apps eine Web-Adresse benötigt.

Für die bequemste Nutzung:
1. `index.html` auf einen privaten Webspace oder z. B. GitHub Pages hochladen.
2. Die Seite einmal in Safari öffnen.
3. Teilen → „Zum Home-Bildschirm“ → „Als Web-App öffnen“.
4. Die Daten bleiben lokal auf dem iPhone. Es wird kein Server für die Bestelldaten benötigt.

Alternativ kann `index.html` direkt in Safari geöffnet werden; dann funktioniert die App ebenfalls lokal, solange Safari die lokalen Browserdaten behält.

Vor dem Löschen/Deinstallieren immer über „Einstellungen → Backup exportieren“ sichern.
