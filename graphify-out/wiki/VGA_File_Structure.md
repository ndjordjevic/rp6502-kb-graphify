# VGA File Structure

> 12 nodes · cohesion 0.17

## Key Concepts

- **VGA firmware main loop and mode dispatch** (7 connections) — `raw/github/picocomputer/rp6502/src/vga/main.c`
- **VGA display mode 1 implementation** (2 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode1.c`
- **VGA display mode 2 implementation** (2 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode2.c`
- **VGA display mode 4 (sprites) implementation** (2 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode4.c`
- **VGA display mode 5 implementation** (2 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode5.c`
- **VGA main.h clock and programming API** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/main.h`
- **VGA mode 1 API** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode1.h`
- **VGA mode 2 API** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode2.h`
- **VGA mode 3 program API declaration** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode3.h`
- **VGA mode 4 API** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode4.h`
- **VGA mode 5 API** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/modes/mode5.h`
- **TinyUSB configuration for VGA build** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/tusb_config.h`

## Relationships

- [[BLE Flash Storage]] (22 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/vga/main.c`
- `raw/github/picocomputer/rp6502/src/vga/main.h`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode1.c`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode1.h`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode2.c`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode2.h`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode3.h`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode4.c`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode4.h`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode5.c`
- `raw/github/picocomputer/rp6502/src/vga/modes/mode5.h`
- `raw/github/picocomputer/rp6502/src/vga/tusb_config.h`

## Audit Trail

- EXTRACTED: 20 (91%)
- INFERRED: 2 (9%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*