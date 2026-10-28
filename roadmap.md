# adding soon :  roadmap ; teaser Pictures ; current features & planned features 

... 

# GeoPyCAD Roadmap

This roadmap contains planned features, improvements and future development goals for GeoPyCAD.

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
| **English translation** | Code cleanup | full scale translation to english & Clean up and restructure the existing codebase | Not finished | 1 |
| **Linux support** | | Native Linux support | Unstable | 4 |
| **Protocols** | Measurements | Protocol generation for measurements | Not started | 4 |
| | Generation / Construction | Protocol generation for construction work | Not started | 4 |
| **Catalogue** | Lines | Catalogue for predefined line types | Brainstorming | 2 |
| | Objects / Blocks | Catalogue for predefined objects and blocks | Brainstorming | 3 |
| | Hatching | Catalogue for predefined hatching patterns | Brainstorming | 3 |
| **Potato form of Earth** | | 3D model of the geoid to explore and visualize the Earth's irregular shape | Prepared / Brainstorming | 5 |
| **Text generation** | | Automated generation of text and descriptions | Brainstorming | 4 |
| **Element Information (Ei)** | Information about selected element | Display information and properties of the currently selected element | Not started | 3 |
| **Construction** | Points | Point construction and creation tools | Unstable | 1 |
| | Lines | Line construction and creation tools | Not started | 1 |
| | Line copy / paste | Copy and paste line elements | Not started | 2 |
| | Line as object | Treat lines as reusable objects | Not started | 2 |
| **More Imports** | XML | Import XML-based measurement / CAD data | Not started | 4 |
| | PKT / PNT | Import point data (`PKT` / `PNT`) | Unstable | 2 |
| | OUT (GeoGraf) | Import GeoGraf `OUT` files | Not started | 4 |
| **Plugin Measurements 3D** | Point to point | Measure the distance between two points in 3D | Prepared / Brainstorming | 3 |
| | Point to line | Measure the distance between a point and a line in 3D | Prepared / Brainstorming | 3 |
| | Angle | Measure angles in 3D | Prepared / Brainstorming | 3 |
| | Angled area | Calculate areas of angled surfaces in 3D | Prepared / Brainstorming | 3 |
| | Polyline length | Calculate the length of a 3D polyline | Prepared / Brainstorming | 3 |
| **Plot** | | Print a selection of graphics / data | WIP | 4 |
| **User Manual** | | Handbook, tips, tricks and explanations | Still updating, no known bugs | 2 |

---

## Implemented and Working

| Feature | Sub-feature | Use / Function | Status | Priority |
|---|---|---|---|---:|
| **Import** | DXF | Import DXF files | Finished, stable | |
| **Visualisation** | 2D | 2D drawing and visualisation | Finished, stable | |
| | 3D | 3D visualisation | Finished, stable | |
| | DXF Viewer | View imported DXF data | Finished, stable | |
| **Parameters** | Background calculation | Perform calculations in the background | Finished, stable | |
| **Plugins** | | Make adding plugins easy | Finished, stable | |
| **Plugin Measurements 2D** | Point to point | Measure the distance between two points | Finished, stable | |
| | Point to line | Measure the distance between a point and a line | Finished, stable | |
| | Angle | Measure angles | Finished, stable | |
| | Flat area | Calculate flat areas | Finished, stable | |
| | Polyline length | Calculate the length of a polyline | Finished, stable | |
| **UI** | Layer display | Display available layers | Finished, stable | |
| | Layer options | Manage layer options | Finished, stable | |
| | Status list | Display object / system status information | Finished, stable | |
| **Viewer** | Grid | Display a coordinate grid | Finished, stable | |
| | Fit to window | Fit the drawing to the available window | Finished, stable | |
| | Background | Switch between black and white background | Finished, stable | |

---

## Status

| Status | Meaning |
|---|---|
| Finished | Feature is implemented and working |
| In progress | Currently being developed |
| Unstable | Implemented but still requires fixes or testing |
| Not finished | Development has started but is not complete |
| Not started | Planned but development has not started |
| Prepared / Brainstorming | Basic preparation or concept exists |
| Brainstorming | Idea / concept stage |

---

## Notes

Priorities are not strict release dates. Features may be implemented in a different order depending on development requirements, dependencies and current development focus.


___

# Änderungsnachweise [DE]
___

Änderungseinfluss auf die Versionsnummer:  

-.+.-   : Punktkonstruktion + Linienkonstruktion  
-.+.-   : Linienkatalog / Datenbank erzeugt  
-.-.+   : 

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
  