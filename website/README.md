# GeoPyCAD Website

Responsive, zweisprachige Projektwebsite für GitHub Pages. Die Gestaltung nutzt ein dunkles CAD-/Blueprint-Thema, technische Liniengrafiken und beim Scrollen sanft erscheinende Panels.

## Lokal ansehen

Öffne `index.html` im Browser. Für die lokale Entwicklung kannst du beispielsweise in VS Code die Erweiterung **Live Server** verwenden.

## Auf GitHub Pages veröffentlichen

1. Lege die Dateien im Repository `testusterror/geopycad` im Website-Ordner ab, oder – falls du ein separates Repository für die Website verwendest – im Root des passenden Pages-Repositories.
2. Für die gewünschte URL `https://testusterror.github.io/geopycad/` muss das Repository `geopycad` heißen und in den Repository-Einstellungen unter **Settings → Pages** entsprechend veröffentlicht werden.
3. Wenn du die Website in einem Unterordner statt im Root deines bestehenden Programm-Repositories ablegst, musst du den Pages-Build entsprechend konfigurieren. GitHub Pages veröffentlicht nicht automatisch einen beliebigen Unterordner.
4. Committe und pushe die Dateien. Warte anschließend auf den Pages-Build.

## Eigenes Hintergrundbild einsetzen

Das bereitgestellte Hintergrundbild liegt unter `assets/background.png`. Der Hero-Bereich verwendet diese Datei bereits als Hintergrund und legt einen dunklen Verlauf darüber, damit Text lesbar bleibt. JPG, PNG oder WebP sind geeignet; bei anderem Dateinamen passe `css/style.css` an.

Empfehlung: ein breites Bild (ca. 2000 px oder mehr), das auch im dunklen Overlay noch genug Motiv zeigt. Vermeide wichtige Details ganz am linken Rand, da dort der Titel liegt.

## Echte Programmausschnitte einsetzen

Die echte 3D-Ansicht liegt unter `assets/screenshots/geopycad-3d.png`. Sie ist der einzige Programmscreenshot auf der Website. Weitere Bereiche verwenden bewusst grafische Illustrationen statt vorgetäuschter Screenshots. Die Platzhalter sollen nicht als echte GeoPyCAD-Screenshots ausgegeben werden.

## Inhalte und Links prüfen

- Der GitHub-Link ist auf `https://github.com/testusterror/geopycad` gesetzt. Passe ihn an, falls dein Repository anders heißt.
- Aussagen über Funktionen sind bewusst vorsichtig formuliert. Bitte passe sie an den tatsächlichen Entwicklungsstand an.
- Roadmap-Texte sind als Entwicklungsfelder gedacht, nicht als verbindliche Termine.

## Sprache

Die Umschaltung DE/EN läuft clientseitig. Die Auswahl wird im Browser lokal gespeichert. Alle sichtbaren Texte sind in `js/site.js` in den Objekten `de` und `en` zentral gepflegt.

## Scroll- und Barrierefreiheit

Die Seite verwendet natürliche Seitenscroll-Bewegung statt Scroll-Locking. Auf größeren Displays erscheinen Panels mit einer subtilen View-Timeline-Animation, sofern der Browser diese unterstützt. Bei `prefers-reduced-motion: reduce` werden Animationen reduziert.
