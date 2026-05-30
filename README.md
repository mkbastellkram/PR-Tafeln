# PR9 Map Focus Variante B — korrigierte Testfassung

Diese ZIP enthält zwei Varianten:

- `index.html` = **selbstständige Ein-Datei-Version**. Alle Bilder sind eingebettet. Diese Datei funktioniert auch dann, wenn GitHub/iPhone/Dateien-App den `assets`-Ordner nicht korrekt mitlädt.
- `index_external_assets.html` = klassische Variante mit separatem `assets/`-Ordner.

Für den schnellen GitHub-Test: `index.html` verwenden.

Fehlerursache der vorherigen Fassung: Die Bilddateien waren technisch vorhanden, aber die HTML-Datei hat sie über relative Pfade wie `assets/pr9_map.webp` geladen. Wenn der Ordner `assets` nicht exakt am selben Ort wie `index.html` liegt oder beim Upload/Entpacken nicht mitgenommen wird, zeigt Safari/GitHub nur Alt-Text bzw. ein Fragezeichen.

# PR9 HTML-Mockup — PR-Explorer

Testbare Einzelroute für GitHub Pages.

## Start

`index.html` öffnen oder den Ordner in ein GitHub-Pages-Repository hochladen.

## Enthalten

- PR9 mobile HTML-Ansicht
- Originalgrafik-Bereiche aus der IFCN-Tafel
- Variante B: Doppeltippen auf die Karte öffnet Vollbildmodus
- Pinch-Zoom bis 200 %
- Info-Button mit Bottom-Sheet zur KI-Übersetzung

## Status

Arbeitsmockup. Texte müssen vor Serienproduktion OCR-/sichtgeprüft werden.
