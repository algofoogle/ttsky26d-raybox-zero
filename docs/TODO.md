# ttsky26d-raybox-zero TODO

*   Use new generated texture set: Stones, door tracks. Probably in a WIP directory somewhere. Remember I had a method to update in GIMP and see result immediately in Verilator.
*   Try to either: fix SDC for FSM; make it a proper FSM rather than "combo logic wait"; or pipeline it (probably not necessary and would bloat logic)
*   SPI regs that control debug options:
    *   IO muxing, including to access:
        *   tex_io0_oe
        *   'current state' marker
    *   Turning on various debug features (map, trace, regs, immediate-load)
*   2xDFF sync on reset and/or async reset
*   Save space by turning texture regs into SIPO (Serial In, Parallel Out) pre-hardened compact macros -- similar to TTsnake
*   Support simple video overlays
*   Tristate Texture QSPI (and maybe all outputs?) during reset
*   Simple sprite (host-controlled): Simple Blit, with optional transparent/not, colour map, X/Y pos, X/Y scale, Z-column knockout, Z-wall-only knockout.
