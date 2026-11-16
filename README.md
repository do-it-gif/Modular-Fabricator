# Modular-Fabricator
A fabricator that can do both additive and subtractive manufacturing on your desktop. How interesting!
# Modular fabricator: CNC and 3D printer on one control hub

A desktop machine platform built as separate modules that share one control and connection hub: a CNC router and an enclosed CoreXY 3D printer today, with room for further modules later.

Course project: Engineering Project Work (10 ECTS), LUT University, September 2026 to April 2027. Team of five: three mechanical, two electrical.

## Status (November 2026)

| Item | Status |
|---|---|
| Concept and module split | Done |
| CAD of the CNC and printer modules | Done, not in this repository yet (see below) |
| Electrical bill of materials | Complete |
| Mechanical bill of materials | About 60% |
| Build | Planned January to April 2027 |

## Modules

| Module | Summary |
|---|---|
| 1. Main control module (hub) | Shared control and connection hub for all modules |
| 2. CNC module | 3-axis moving gantry supported at both ends with auto-squared Y, ball-screw linear axes, 1.5 kW ER16 spindle with VFD; laid out so a tilt head and rotary table can be added for 5-axis work. Requirement: cut softwood through steel at variable spindle speed |
| 3. Printer module | Enclosed CoreXY, about 180 mm cube, Klipper on an Octopus board with a CAN toolhead; single Z screw with two linear rails |

## Budget from the bill of materials

| Module | Electrical (EUR) | Mechanical (EUR) | Tooling (EUR) | Module total (EUR) |
|---|---|---|---|---|
| Main control module | 297-369 | 20 | 0 | 317-389 |
| CNC module | 715-848 | 298-435 | 37-53 | 1050-1336 |
| Printer module | 247-317 | 126-213 | 0 | 373-530 |
| **System** | **1259-1534** | **444-668** | **37-53** | **1740-2255** |

Mechanical cost assumes plate stock, bed and guard panels come from the university workshop.

## My part

The 3D-printer module, mainly the carriage, plus the electrical bill of materials and the wiring plan for all modules.

## In this repository

- `Fabricator_BOM.docx`: full bill of materials with part roles, options, checks before ordering and subtotals

## Not here yet

The SolidWorks assemblies are larger than GitHub's browser upload limit. They will be added as STEP exports or as a release archive.


