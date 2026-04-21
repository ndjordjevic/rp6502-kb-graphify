# HID Keyboard/Mouse

> 8 nodes · cohesion 0.25

## Key Concepts

- **RIA HID keyboard driver and layout selection (kbd.c)** (4 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- **RIA HID report descriptor parsing and bit extraction** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/hid.c`
- **RIA str.h API and string literal declarations** (2 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.h`
- **Polish programmer keyboard layout tables** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd_pl.h`
- **US and US-INTL keyboard layout tables** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd_us.h`
- **RIA HID mouse driver API** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/mou.h`
- **RIA HID gamepad driver (pad.c)** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **RIA string utilities and flash string tables (str.c)** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.c`

## Relationships

- [[FatFS DiskIO Bridge]] (14 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/hid/hid.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd_pl.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd_us.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/mou.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- `raw/github/picocomputer/rp6502/src/ria/str/str.h`

## Audit Trail

- EXTRACTED: 8 (57%)
- INFERRED: 6 (43%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*