# M568 Assignment Module · Routing

Ward-Beck Systems M568, 1985|18. Wiki page: [M568 on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/PAGES/M568.html)

| Folder | What is in it | Files |
|---|---|---|
| [SCHEMATICS/](SCHEMATICS/) | electrical drawings: schematics, functional diagrams, component layouts, wiring | 20 |
| [MECHANICAL/](MECHANICAL/) | front panels, cover plates, metalwork, assemblies; the front panel as vectors | 7 |
| [PINOUTS/](PINOUTS/) | the RTO-144 connector: connection sheets, connector layouts, rear views | 1 |
| [PHOTOS/](PHOTOS/) | photographs of the module | 1 |
| [KICAD/](KICAD/) | KiCad schematics traced from the drawings, the symbol, PCB projects | 6 |
| [OCR/](OCR/) | the note of every file: date, origin, title block, OCR text | 6 |

<!-- module data: tools/module_specs.py, tools/forum_quotes.py -->

**On the WBSps forum (2006|39 - 2014|47):** [1 topic](FORUM.md): what owners and technicians said about it.

<!-- /module data -->

## Mechanical

_Mechanical drawings: front panels, cover plates, metalwork and hardware (-03- drawings), AutoCAD files, each with its `(EXTRACTED).svg` vectors; `<module> - front panel.svg` is the front panel as vectors._

## 3-D model

[`MECHANICAL/M568.stl`](MECHANICAL/M568.stl) (GitHub turns it in 3-D) · [view, change and generate it on WBSps.ca](https://wardbecksystems.github.io/WBSps.ca/2026/stl.html?m=M568)

- **Size:** 41 × 178 mm panel, 165 mm deep, 3.2 mm plate (assumed: 1.6" x 7" x 6.5", the common module)
- **From the drawing:** 0 holes and cut-outs, 0 knobs (front panel: `MECHANICAL/M568 - front panel.svg`)
- no drawing of the front panel: the panel is blank
- Made by `tools/module_models.py` (→ `MECHANICAL/M568.model.json`) and `tools/stl/make_stl.mjs` in [WBSps.ca](https://github.com/WardBeckSystems/WBSps.ca); the site makes the same STL from the same JSON.

## Schematics

_Electrical drawings: schematics (-02-), functional diagrams (-01-), component layouts (-06-), wiring (-09-), PCB files (.pcb .dsn), and beside each scan its `(EXTRACTED).svg`: the vectors traced from it._

<table>
<tr><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1o08YX2pJtFzxf3g28YKOprwv29l678kB/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1o08YX2pJtFzxf3g28YKOprwv29l678kB" width="240" alt="1987 - 568-02-016 - M568R MIC SEL MASTER ASSIGN MODULE SCHEMATIC - DRN PA - ENG PA - ISS 1.jpg"></a><br><sub>1987|20 · 568-02-016 - M568R MIC SEL MASTER ASSIGN MODULE SCHEMATIC - DRN PA - ENG PA - ISS 1 · <a href="SCHEMATICS/1987%20-%20568-02-016%20-%20M568R%20MIC%20SEL%20MASTER%20ASSIGN%20MODULE%20SCHEMATIC%20-%20DRN%20PA%20-%20ENG%20PA%20-%20ISS%201%20(EXTRACTED).svg">vectors</a></sub></td><td align="center" valign="top" width="33%"><a href="https://drive.google.com/file/d/1BGf7XFRHHKO6gCYomHEH5EpBH3YUV-i5/view" title="Open on Google Drive"><img src="https://drive.google.com/thumbnail?sz=w480&id=1BGf7XFRHHKO6gCYomHEH5EpBH3YUV-i5" width="240" alt="1987 - 568-02-017 - M568S MIC SEL MASTER ASSIGN MODULE SCHEMATIC - DRN PA - ENG PA - ISS 1.jpg"></a><br><sub>1987|20 · 568-02-017 - M568S MIC SEL MASTER ASSIGN MODULE SCHEMATIC - DRN PA - ENG PA - ISS 1 · <a href="SCHEMATICS/1987%20-%20568-02-017%20-%20M568S%20MIC%20SEL%20MASTER%20ASSIGN%20MODULE%20SCHEMATIC%20-%20DRN%20PA%20-%20ENG%20PA%20-%20ISS%201%20(EXTRACTED).svg">vectors</a></sub></td></tr>
</table>

## KiCad

_KiCad: a schematic (`.kicad_sch`) traced from each electrical drawing, the module symbol (`.kicad_sym`) and its PCB projects. Traced schematics are the line work only: redraw with symbols over them._

- [1985 - 568-01-004 - M568C M568D TRACK MASTER FUNCTIONAL - ENG ECJ - ISS 2.kicad_sch](KICAD/1985%20-%20568-01-004%20-%20M568C%20M568D%20TRACK%20MASTER%20FUNCTIONAL%20-%20ENG%20ECJ%20-%20ISS%202.kicad_sch)
- [1987 - 568-02-016 - M568R MIC SEL MASTER ASSIGN MODULE SCHEMATIC - DRN PA - ENG PA - ISS 1.kicad_sch](KICAD/1987%20-%20568-02-016%20-%20M568R%20MIC%20SEL%20MASTER%20ASSIGN%20MODULE%20SCHEMATIC%20-%20DRN%20PA%20-%20ENG%20PA%20-%20ISS%201.kicad_sch)
- [1987 - 568-02-017 - M568S MIC SEL MASTER ASSIGN MODULE SCHEMATIC - DRN PA - ENG PA - ISS 1.kicad_sch](KICAD/1987%20-%20568-02-017%20-%20M568S%20MIC%20SEL%20MASTER%20ASSIGN%20MODULE%20SCHEMATIC%20-%20DRN%20PA%20-%20ENG%20PA%20-%20ISS%201.kicad_sch)
- [19xx - 568-02-018 - M568T LINE SEL MASTER ASSIGN MODULE SCHEMATIC - DRN DBS - ENG DBS - ISS 1.kicad_sch](KICAD/19xx%20-%20568-02-018%20-%20M568T%20LINE%20SEL%20MASTER%20ASSIGN%20MODULE%20SCHEMATIC%20-%20DRN%20DBS%20-%20ENG%20DBS%20-%20ISS%201.kicad_sch)
- [19xx - 568-02-019 - M568U ASSIGNMENT MODULE SCHEMATIC - DRN GEB - ISS 1.kicad_sch](KICAD/19xx%20-%20568-02-019%20-%20M568U%20ASSIGNMENT%20MODULE%20SCHEMATIC%20-%20DRN%20GEB%20-%20ISS%201.kicad_sch)
- [M568.kicad_sym](KICAD/M568.kicad_sym)

---
Archive: Anthony Peter Kuzub · [WBSps.ca](https://WBSps.ca) · [WBSps.Kuzub.com](https://WBSps.Kuzub.com)
