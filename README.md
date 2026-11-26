# Wal Mk II bass preamp: reverse-engineering notes

Schematics, a breadboard build and a parts list for the two-board Wal Mk II bass preamp, traced from a 2007 instrument. Shared for repair and study.

**Status, 26 November 2026:** work in progress. Both boards have been traced and rung out with a meter. Nothing here has yet been built or tested, and every predicted figure is calculated, not measured.

## Contents

| Folder | What is in it |
|---|---|
| `schematics/` | The KiCad schematic, draft v0.5 (three sheets), and the same circuit drawn on one sheet (PDF and PNG) |
| `breadboard/` | A build sheet for a two-breadboard version, the wiring diagram for each board (PDF and PNG) and the wiring list (CSV) |
| `parts/` | The parts list for one set, with supplier links and prices (spreadsheet and PDF) |

## Reading the files

- Reference designators (R1, C1 and so on) follow the KiCad schematic, draft v0.5. The one-sheet drawing uses placement-map numbers (A1, B1 and so on) instead.
- "Fretted" and "fretless" in the drawing notes are the two instruments studied. Folder names in those notes, such as "00 Working files", are working files that are not in this repository.
- The breadboard build uses ordinary pots and no transformer, so its parts list differs from the main one. The build sheet says where.
- The original board carries an OEP A262A5E transformer, which is not on sale and has no published data. The parts list uses the A262A3E in its place.
- Prices and stock were read on 23 and 24 November 2026 and will change.

## Acknowledgements

The schematic notes refer to earlier community traces by Kinkh and Dario.

## Disclaimer

This is an unofficial project and is not affiliated with or endorsed by Wal or Electric Wood. Names and trademarks belong to their owners. The material is offered as is, with no warranty that it is correct or fit for any purpose.

No licence has been chosen yet.
