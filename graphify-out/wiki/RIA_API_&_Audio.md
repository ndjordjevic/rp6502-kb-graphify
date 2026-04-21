# RIA API & Audio

> 148 nodes · cohesion 0.02

## Key Concepts

- **init()** (27 connections) — `raw/github/picocomputer/rp6502/src/vga/main.c`
- **vga.c** (27 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/vga.c`
- **ria.c** (22 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/ria.c`
- **com.c** (21 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/com.c`
- **stop()** (20 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **task()** (17 connections) — `raw/github/picocomputer/rp6502/src/vga/main.c`
- **cpu.c** (15 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/cpu.c`
- **main.c** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **vga_connect()** (11 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/vga.c`
- **com_task()** (10 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/com.c`
- **break_()** (10 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **run()** (10 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **pix_send_blocking()** (10 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/pix.h`
- **vga_task()** (10 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/vga.c`
- **com_uart_task()** (9 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/com.c`
- **main()** (9 connections) — `raw/github/picocomputer/rp6502/src/vga/main.c`
- **com_tx_fanout()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/com.c`
- **pix_ready()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/pix.h`
- **bel.c** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/aud/bel.c`
- **com.h** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/com.h`
- **pix.c** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/pix.c`
- **vga_init()** (8 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/vga.c`
- **cpu_change_phi2_khz()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/cpu.c`
- **main_stop()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **aud.c** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/aud/aud.c`
- *... and 123 more nodes in this community*

## Relationships

- [[RP2040 USB HCD]] (136 shared connections)
- [[USB Host/Device Stack]] (73 shared connections)
- [[FatFS & Config Core]] (34 shared connections)
- [[FatFS Internals]] (24 shared connections)
- [[VGA Core Runtime]] (18 shared connections)
- [[RIA Register Interface]] (14 shared connections)
- [[VGA CDC Serial]] (9 shared connections)
- [[OPL2 Signal Processing]] (7 shared connections)
- [[VGA Mode4 Affine Transform]] (5 shared connections)
- [[TCP/IP Network Stack]] (3 shared connections)
- [[Network AT Commands]] (3 shared connections)
- [[RIA Readline/Terminal]] (1 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- `raw/github/picocomputer/rp6502/src/ria/api/clk.c`
- `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- `raw/github/picocomputer/rp6502/src/ria/api/pro.c`
- `raw/github/picocomputer/rp6502/src/ria/api/std.c`
- `raw/github/picocomputer/rp6502/src/ria/aud/aud.c`
- `raw/github/picocomputer/rp6502/src/ria/aud/aud.h`
- `raw/github/picocomputer/rp6502/src/ria/aud/bel.c`
- `raw/github/picocomputer/rp6502/src/ria/aud/bel.h`
- `raw/github/picocomputer/rp6502/src/ria/aud/opl.c`
- `raw/github/picocomputer/rp6502/src/ria/aud/opl.h`
- `raw/github/picocomputer/rp6502/src/ria/aud/psg.c`
- `raw/github/picocomputer/rp6502/src/ria/aud/psg.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- `raw/github/picocomputer/rp6502/src/ria/main.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/fil.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/ram.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/set.c`

## Audit Trail

- EXTRACTED: 430 (64%)
- INFERRED: 245 (36%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*