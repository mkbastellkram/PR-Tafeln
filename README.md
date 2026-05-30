# PR9 Map Focus Variante B — v2

Testbare HTML-Arbeitsfassung für GitHub Pages.

## Start

Für den iPhone-Test `index.html` öffnen oder über GitHub Pages bereitstellen.

## Enthalten

- selbstständige `index.html` mit eingebetteten Bilddaten
- `index_external_assets.html` mit externen Assets
- `assets/` mit Preview- und Fullres-Bildquellen

## Geändert gegenüber v1

- Karte neu und großzügiger aus Originaltafel extrahiert
- Highres-Karte für Vollbildmodus getrennt von Preview-Ansicht
- Apple-Fotos-artiges Vollbild-Overlay statt halbem Bottom-Sheet
- Doppeltipp auf Karte öffnet direkt Vollbild
- Doppeltipp im Vollbild toggelt 100 % / 200 %
- Swipe-down schließt nur bei 100 % Zoom
- Fotos als horizontaler Swipe-Slider
- Zuschnitte mit Sicherheitsrändern

## Produktionshinweis

Die PR9-Zuschnitte sind individuell geprüft. Für weitere PR-Tafeln keine starren Pixelmasken verwenden, sondern jeweils Layout-Scan + adaptive Segmentierung.
