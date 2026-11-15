# Grid Box Generator

Modulare Boxen im Raster, verbunden mit Bowtie-Keys (Schwalbenschwanz). Boxen im Browser anordnen, Maße eingeben und als 3MF oder STL für den 3D-Druck herunterladen. Ein Server ist nicht nötig, alles läuft im Browser.

## Funktionen

- Mehrere Boxen andocken, in der 3D-Ansicht vergrößern, verkleinern und verschieben
- Maße außen (Raster) oder innen angeben
- Taschen pro Seite abschaltbar, z.B. für Abschlussboxen am Rand
- Optionaler Deckel mit Falz
- Keys werden passend zu den Verbindungen berechnet
- Export als 3MF (alle Teile druckfertig) oder als STL
- Toleranztest zum Einstellen des Spiels

## Veröffentlichen mit GitHub Pages

1. Neues **öffentliches** Repository anlegen.
2. `index.html` (und gern diese README) hochladen.
3. Unter **Settings → Pages** als Quelle „Deploy from a branch“, Branch `main`, Ordner `/ (root)` wählen und speichern.
4. Nach ein bis zwei Minuten ist die Seite unter `https://<name>.github.io/<repository>/` erreichbar.

Für ein Update einfach eine neue `index.html` hochladen.

## Verwendete Bibliotheken

- [manifold-3d](https://github.com/elalish/manifold) (Apache-2.0) für die Geometrie. Die WebAssembly-Datei ist in `index.html` eingebettet.
- [three.js](https://threejs.org) (MIT) für die 3D-Ansicht, geladen über jsDelivr.
- IBM Plex Sans und Mono (SIL Open Font License), geladen über Google Fonts.
