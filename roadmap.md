# GeoPyCAD Roadmap

This roadmap outlines planned features, improvements and longer-term development goals for GeoPyCAD. Priorities indicate relative importance, not release dates.

## Priority Levels

| Level | Meaning |
|---:|---|
| 1 | Must be done ASAP |
| 2 | Should be done next |
| 3 | Would be nice to have ASAP |
| 4 | Would be nice to have someday |
| 5 | One more thing to add, I guess |
| 6 | Meh. Not really needed, but nice to have |
| 7 | / |
| 8 | / |
| 9 | / |
| 10 | Some day |

---

## Roadmap

| Feature | Sub-feature | Use / Function | Status | Priority |
|---|---|---|---|---:|
| **Codebase and translations** | Code cleanup | Clean up and restructure the existing codebase | Not finished | 1 |
| | Translation profiles | Expand translations and complete the English UI using separate language files | In progress | 1 |
| **Construction** | Points | Point construction and creation tools | Unstable | 1 |
| | Lines | Line construction and creation tools | Not started | 1 |
| | Line copy / paste | Copy and paste line elements | Not started | 2 |
| | Line as object | Treat lines as reusable objects | Not started | 2 |
| **Catalogue / database** | Lines | Catalogue/database for predefined line types | In progress | 2 |
| | Objects / blocks | Catalogue for reusable objects and blocks | Brainstorming | 3 |
| | Point symbols | Make small projects importable and reusable as point symbols | Not started | 3 |
| | Hatching | Catalogue for predefined hatching patterns | Brainstorming | 3 |
| | Project database | Save and manage project data in a database | Not started | 3 |
| **More imports and exchange** | PKT / PNT | Improve import of point data (`PKT` / `PNT`) | Unstable | 2 |
| | XML | Import XML-based surveying / CAD data | Not started | 4 |
| | OUT (GeoGraf) | Import GeoGraf `OUT` files | Not started | 4 |
| | DWG / DXF export | Reliable DWG/DXF import and export as a longer-term 2.0 goal | Not started | 2 |
| **Linux support** | Native Linux | Improve native Linux support and stability | Unstable | 4 |
| **Protocols** | Measurements | Generate measurement protocols | Not started | 4 |
| | Construction | Generate protocols for construction work | Not started | 4 |
| **Terrain / surface model** | DTM / DGM | Develop a more direct terrain-model workflow | Brainstorming | 4 |
| **Text generation** | Text and descriptions | Automated generation of text and descriptions | Brainstorming | 4 |
| **Element Information (Ei)** | Selected element | Display information and properties of the currently selected element | Not started | 3 |
| **Event logs** | Events / operations | Add event or operation logs | Brainstorming | 4 |
| **Plugin Measurements 3D** | Point to point | Measure the distance between two points in 3D | Prepared / Brainstorming | 3 |
| | Point to line | Measure the distance between a point and a line in 3D | Prepared / Brainstorming | 3 |
| | Angle | Measure angles in 3D | Prepared / Brainstorming | 3 |
| | Angled area | Calculate areas of angled surfaces in 3D | Prepared / Brainstorming | 3 |
| | Polyline length | Calculate the length of a 3D polyline | Prepared / Brainstorming | 3 |
| **Plot** | Layout and output | Continue improving print/plot output and layout controls | In progress | 4 |
| **User Manual** | Documentation | Keep the handbook, tips, tricks and explanations up to date | In progress | 2 |
| **Potato form of Earth** | Geoid model | 3D model to explore and visualise the Earth's irregular shape | Prepared / Brainstorming | 5 |

---

## Implemented and Working

| Feature | Sub-feature | Use / Function | Status |
|---|---|---|---|
| **Import** | DXF | Import DXF files | Finished, stable |
| **Visualisation** | 2D | 2D drawing and visualisation | Finished, stable |
| | 3D | 3D visualisation | Finished, stable |
| | DXF Viewer | View imported DXF data | Finished, stable |
| **Parameters** | Background calculation | Perform calculations in the background | Finished, stable |
| **Plugins** | Plugin support | Make adding plugins straightforward | Finished, stable |
| **Plugin Measurements 2D** | Point to point | Measure the distance between two points | Finished, stable |
| | Point to line | Measure the distance between a point and a line | Finished, stable |
| | Angle | Measure angles | Finished, stable |
| | Flat area | Calculate flat areas | Finished, stable |
| | Polyline length | Calculate the length of a polyline | Finished, stable |
| **UI** | Layer display | Display available layers | Finished, stable |
| | Layer options | Manage layer options | Finished, stable |
| | Status list | Display object / system status information | Finished, stable |
| **Viewer** | Grid | Display a coordinate grid | Finished, stable |
| | Fit to window | Fit the drawing to the available window | Finished, stable |
| | Background | Switch between black and white backgrounds | Finished, stable |
| **Language system** | Translation files | Load language profiles from separate translation files | Integrated; translations ongoing |
| **Plot UI** | Graphics and plot tabs | Graphics tab, plot tabs and plot settings | Implemented; continued development |
| **Design** | Standard and custom | Standard and custom appearance options | Implemented |

---

## Versioning Notes

The current changelog uses the following intended versioning convention:

- `1.-.-` — major technical milestone (for example, the origin-shift discovery in version 1.0)
- `-.1.-` — expansion of a major function (for example, measurement tools or language support)
- `-.-.1` — smaller feature additions
- `-.-.-.a` — bug fixes for the previous version

Version `2.0` is described as a longer-term goal for reliable DWG/DXF import and export. This is a goal, not a committed release date.

## Status Definitions

| Status | Meaning |
|---|---|
| Finished, stable | Implemented and working reliably |
| Implemented | Available, but may continue to evolve |
| In progress | Currently being developed |
| Unstable | Implemented but still requires fixes or testing |
| Not finished | Development has started but is not complete |
| Not started | Planned but development has not started |
| Prepared / Brainstorming | Basic preparation or concept exists |
| Brainstorming | Idea / concept stage |

## Notes

Priorities are not strict release dates. Features may be implemented in a different order depending on dependencies, testing, and the current development focus. Statuses reflect the supplied roadmap and changelog notes and should be updated as implementation progresses.

---


Deutsch und minimalistisch
## Roadmap

1. Code aufräumen
2. Sprachen weiter umwandeln
3. Punktkonstruktion
4. linienkonstruktion
5. Datenbank - Linien
6. Datenbank - Projekt : Speichern als Datenbank
7. Datenbank - Punksymbole : miniprojekte als Punksymbole importierbar machen
8. DGM - komplett direkt 
9. geschehniss-Protokolle 

---

VERIONSnr. 
1.-.- = Knackpunkt (1.0 war OriginShift entdeckung);
-.1.- = Hauptfunktionen erweitert (x.1= MessenTool, x.2=Sprachen;  )
-.-.1 = kleinere Erweiterungen
-.-.-.a = Bugfixes

2.0 ist :  fehlerfreier DWG/DXF = Import/Export
___

# Änderungsnachweise [DE]
___

Änderungseinfluss auf die Versionsnummer:  

-.+.-   : Punktkonstruktion + Linienkonstruktion  
-.+.-   : Linienkatalog / Datenbank erzeugt  
-.-.+   : 
-.-.-.a : Fehlerbehebung der letzten Version

___
### Versionsnummer  

1.2.13  - Design Standard + custom  
1.2.12  - Sprachen integriert (über eigene Übersetzungsdateien)  
1.2.11  - Gafik-Tab, Plot-Tabs mit Ploteinstellungen  
1.2.10  - Menüreiter in App.py erweitert  
1.2.9   - Konstruktion(Placeholder), Messen (funktionsfähig)  
1.1.9   - Pluginsupport  

1.0.9   - Benutzerhandbuch  
1.0.8   - Fehlerbehebung  
1.0.7   - Fehlerbehebung  
1.0.6   - Fehlerbehebung  
1.0.5   - 3D/2D Switch Ansicht, HUD in 3D  
1.0.4   - Hintergrundparameter (Rechenparameter)  
1.0.3   - Fehlerbehebung  
1.0.2   - DXF: Kreise  
1.0.1   - DXF: Textgrößen richtig wie in DXF  
1.0     - Originshift entdeckt und somit den Pfad gelegt für eine gute Darstellung und   

0.9     - stablile App draus gemacht  
0.6-0.8 - Fehlerbehebung  
0.5     - DXF Darstellung annähernd nachvorllziehbar  
0.2-0.4 - Fehlerbehebung  
0.1     - funktionierender DXF import - (reiner DXF-Viewer)  
  