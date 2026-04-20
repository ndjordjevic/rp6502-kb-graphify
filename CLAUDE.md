# rp6502-kb-graphify

Knowledge graph of the RP6502 Picocomputer ecosystem, auto-built by graphify from the same raw sources as `rp6502-kb`.

The graph lives in `graphify-out/`. Start with `graphify-out/GRAPH_REPORT.md` for god nodes and community structure, then browse `graphify-out/wiki/` for per-community articles, or open `graphify-out/graph.html` for the interactive view.

---

## Domain vocabulary

Always use these spellings exactly:

`RP6502`, `RP6502-RIA`, `RP6502-RIA-W`, `RP6502-VGA`, `RP6502-OS`, `RIA`, `PHI2`, `PIX bus`,
`65C02`, `W65C02S`, `cc65`, `llvm-mos`, `RP2040`, `RP2350`, `Pi Pico 2`, `PIO`, `VGA`, `VSYNC`, `HSYNC`

---

## What this covers

- **Hardware:** RP6502 board, RIA firmware (RP2040), VGA firmware (RP2350/Pi Pico 2), PIX bus
- **Software:** 65C02 assembly, cc65 C toolchain, llvm-mos, RP6502-OS API
- **Community:** Discord tips, known bugs, workarounds, rumbledethumps design decisions

Out of scope: general Pico/RP2040 topics not specific to RP6502.

---

## Raw sources

| Folder | Contents |
|---|---|
| `raw/pdfs/` | 7 PDFs — RP6502 schematic, W65C02S, RP2040/RP2350 datasheets, Pico C SDK, Pico C book |
| `raw/web/` | Markdown clips — picocomputer.github.io, cc65 docs, 6502.org |
| `raw/youtube/` | 21 YouTube transcript `.md` files (Picocomputer 6502 playlist) |
| `raw/discord/` | 2 Discord `.txt` exports (rumbledethumps server: #chat, #razemos) |
| `raw/github/` | 8 repos: `picocomputer/rp6502`, `picocomputer/examples`, `picocomputer/adventure`, etc. |
