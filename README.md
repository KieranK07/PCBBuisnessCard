# PCB Business Card

A business card that is a printed circuit board. Two layers, 1.6 mm, card-sized.
This repo holds the fab outputs — Gerbers and drill files — ready to upload to a board house.

## Attribution

This started from a third-party KiCad business-card template, which is why every file is
still named `Shawn_PCB_Business_card-*` and why that project name appears in the Gerber
headers (`%TF.ProjectId,Shawn_PCB_Business_card%`). The layout was modified from there in
KiCad 9.0.4. The original template author retains credit for the base design.

## What's here

Eleven fab outputs: copper, silkscreen and solder mask for both sides, the board outline,
plated and non-plated drill files, and the two drill maps.

The KiCad sources (`.kicad_pcb`, `.kicad_sch`) are **not** in this repo, so you can send
these files to a fab but you cannot open the design and edit it.

## Ordering

Upload the `.gbr` and `.drl` files to [JLCPCB](https://jlcpcb.com/),
[PCBWay](https://www.pcbway.com/) or [OSH Park](https://oshpark.com/).

| setting | value |
| :--- | :--- |
| layers | 2 |
| thickness | 1.6 mm |
| finish | ENIG — gold, and it looks considerably better than HASL on a card |

## Status

Fab outputs only. Not verified by an actual board order, so check the outline and drill
alignment in your fab's Gerber viewer before paying for it.
