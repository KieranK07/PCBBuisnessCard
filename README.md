# PCB Business Card

A custom PCB business card designed in [KiCad](https://www.kicad.org/) (version 9.0.4).

## Overview

This project contains the manufacturing files (Gerber files and drill files) for a custom PCB business card. Instead of a traditional paper card, this design is a functional printed circuit board in business card form factor.

## Files

| File | Description |
|------|-------------|
| `Shawn_PCB_Business_card-CuTop.gbr` | Top copper layer |
| `Shawn_PCB_Business_card-CuBottom.gbr` | Bottom copper layer |
| `Shawn_PCB_Business_card-SilkTop.gbr` | Top silkscreen layer |
| `Shawn_PCB_Business_card-SilkBottom.gbr` | Bottom silkscreen layer |
| `Shawn_PCB_Business_card-MaskTop.gbr` | Top solder mask layer |
| `Shawn_PCB_Business_card-MaskBottom.gbr` | Bottom solder mask layer |
| `Shawn_PCB_Business_card-EdgeCuts.gbr` | Board outline (edge cuts) |
| `Shawn_PCB_Business_card-PTH.drl` | Plated through-hole drill file |
| `Shawn_PCB_Business_card-NPTH.drl` | Non-plated through-hole drill file |
| `Shawn_PCB_Business_card-PTH-drl_map.pdf` | Plated drill map (PDF) |
| `Shawn_PCB_Business_card-NPTH-drl_map.pdf` | Non-plated drill map (PDF) |

## Manufacturing

To order this PCB, upload the Gerber (`.gbr`) and drill (`.drl`) files to a PCB manufacturer such as:

- [JLCPCB](https://jlcpcb.com/)
- [PCBWay](https://www.pcbway.com/)
- [OSH Park](https://oshpark.com/)

### Recommended Specs

- **Layers:** 2
- **Board thickness:** 1.6 mm
- **Finish:** ENIG (gold finish) recommended for aesthetics

## Tools Used

- **KiCad** 9.0.4 — PCB design software
