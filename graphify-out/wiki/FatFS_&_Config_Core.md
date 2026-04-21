# FatFS & Config Core

> 156 nodes · cohesion 0.04

## Key Concepts

- **mon_add_response_str()** (51 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **rom.c** (36 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- **str_parse_end()** (32 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- **set.c** (30 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/set.c`
- **str_parse_string()** (29 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- **mon_add_response_fn()** (28 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **mon.c** (22 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **pro.c** (18 connections) — `raw/github/picocomputer/rp6502/src/ria/api/pro.c`
- **str_parse_uint32()** (16 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- **mon_add_response_fatfs()** (15 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **fil.c** (15 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/fil.c`
- **mon_task()** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **ram.c** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/ram.c`
- **rom_mon_install()** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- **pro_nfc()** (13 connections) — `raw/github/picocomputer/rp6502/src/ria/api/pro.c`
- **rom_open()** (13 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- **mon_add_response_lfs()** (11 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **rom_exec()** (11 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- **f_closedir()** (10 connections) — `raw/github/picocomputer/rp6502/src/fatfs/ff.c`
- **fil_mon_chdir()** (9 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/fil.c`
- **pro_api_exec()** (9 connections) — `raw/github/picocomputer/rp6502/src/ria/api/pro.c`
- **rom_load_argv()** (9 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- **fil_com_rx_mbuf()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/fil.c`
- **fil_mon_upload()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/fil.c`
- **str.c** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- *... and 131 more nodes in this community*

## Relationships

- [[RP2040 USB HCD]] (98 shared connections)
- [[VGA Core Runtime]] (32 shared connections)
- [[BLE HID/HCI Stack]] (22 shared connections)
- [[RIA API & Audio]] (19 shared connections)
- [[FatFS Internals]] (14 shared connections)
- [[Network AT Commands]] (7 shared connections)
- [[RIA Register Interface]] (7 shared connections)
- [[TCP/IP Network Stack]] (5 shared connections)
- [[VGA Mode1 Graphics]] (3 shared connections)
- [[VGA CDC Serial]] (3 shared connections)
- [[RIA Clock & Errno]] (1 shared connections)
- [[USB Host/Device Stack]] (1 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/fatfs/ff.c`
- `raw/github/picocomputer/rp6502/src/ria/api/pro.c`
- `raw/github/picocomputer/rp6502/src/ria/main.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/fil.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/hlp.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/ram.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/set.c`
- `raw/github/picocomputer/rp6502/src/ria/net/tel.c`
- `raw/github/picocomputer/rp6502/src/ria/str/rln.c`
- `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/cfg.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/cpu.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/mem.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/ria.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/sys.c`
- `raw/github/picocomputer/rp6502/src/ria/usb/msc.c`
- `raw/github/picocomputer/rp6502/src/ria/usb/nfc.c`

## Audit Trail

- EXTRACTED: 502 (50%)
- INFERRED: 505 (50%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*