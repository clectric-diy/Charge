# Daisy Seed Breakout

This module provides a breakout concept for the Electrosmith Daisy Seed with pinout-focused silkscreen references and supporting manufacturing assets.

## Purpose

Provide an easier way to integrate a Daisy Seed into breadboard and panel prototypes while preserving access to the module pinout and adding visual wiring references.

## Subdirectories

- [Breakout](Breakout/): KiCad source for the breakout PCB.
- [Discovery](Discovery/): BOM snapshot for a discovery/prototype variant.
- [docs](docs/): renderings and early design sketches.
- [Silkscreen](Silkscreen/): exported silkscreen artwork and source graphics.

## Included Design Assets

- KiCad project: `Breakout/KiCad/Charge-Seed-Breakout.kicad_*`
- BOM: `Breakout/KiCad/BOM-Charge-Seed-Breakout.csv`
- Additional BOM: `Discovery/BOM_Charge-Seed-Discovery_v1.csv`

## Components

Component details, BOM entries, and manufacturer part numbers will be expanded here as this breakout board is developed.

- See the `Key Components (From Tracked BOMs)` table below.
- Additional passives, protection parts, and mechanical hardware: TBD

## Key Components (From Tracked BOMs)

| Variant | Designators | Qty | MPN/Designation | Manufacturer |
| --- | --- | --- | --- | --- |
| Breakout | U8,U7,U4,U5 | 4 | 2541FV-20P-B | Not specified in CSV |
| Breakout | U3,U6 | 2 | P125-1120A0BS116A1 | Not specified in CSV |
| Breakout | U1,U9,U2,U10 | 4 | JL308-25410G01 | Not specified in CSV |
| Discovery | ENC | 1 | PEC11R-4215K-S0012 | Bourns |

## Notes

The historical notes and renders in this directory indicate an emphasis on on-board pin reference graphics and discoverability while wiring the Daisy Seed.
