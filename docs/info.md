<!---

This file is used to generate your project datasheet. Please fill in the information below and delete any unused
sections.

You can also include images in this folder and reference them in the markdown. Each image must be less than
512 kb in size, and the combined size of all images must be less than 1 MB.
-->

## How it works

This project is a framebuffer-less VGA display generator (i.e. it is 'racing the beam') that produces a simple implementation of a "3D"-like ray casting game engine... just the graphics part of it. It is inspired by Wolfenstein 3D, using a map that is a grid of wall blocks, with basic texture mapping.

For some previous tapeouts of this project, see:

*   2026-07: [gf180ws2-raybox-zero](https://github.com/algofoogle/gf180ws2-raybox-zero): wafer.space Run #2 full-chip gf180mcuD version.
*   2026-03: [ttihp0p4-raybox-zero](https://github.com/algofoogle/ttihp0p4-raybox-zero): TT experimental IHP shuttle on SG13CSMO5L PDK.
*   2025-12: [ttgf0p2-raybox-zero](https://github.com/algofoogle/ttgf0p2-raybox-zero): TT experimental gf180mcuD shuttle on wafer.space Run #1.
*   2025-06: [ttcad25a-raybox-zero](https://github.com/algofoogle/ttcad25a-raybox-zero): sky130A version on a TT run for a shuttle organised by Cadence.


## How to test

TBC. Please contact me if you want to know something in particular and I'll put it into the documentation!

Supply a clock in the range of 21-31.5MHz; 25.175MHz is ideal because this is meant to be "standard" VGA 640x480\@59.94Hz, and note that the design may not be stable above that.


## External hardware

Tiny VGA PMOD on dedicated outputs (`uo`).

Optional SPI controllers to drive `ui_in[2:0]`.

TBC. Please contact me if you want to know something in particular and I'll put it into the documentation!

