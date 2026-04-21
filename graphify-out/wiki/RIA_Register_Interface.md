# RIA Register Interface

> 110 nodes · cohesion 0.05

## Key Concepts

- **main_api()** (45 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **api_return_ax()** (39 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **api_return_errno()** (33 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **api.h** (25 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **dir.c** (22 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- **std.c** (21 connections) — `raw/github/picocomputer/rp6502/src/ria/api/std.c`
- **api_return_fresult()** (19 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **clk.c** (15 connections) — `raw/github/picocomputer/rp6502/src/ria/api/clk.c`
- **api_return_axsreg()** (12 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **api.c** (12 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- **atr_api_get()** (11 connections) — `raw/github/picocomputer/rp6502/src/ria/api/atr.c`
- **atr_api_set()** (11 connections) — `raw/github/picocomputer/rp6502/src/ria/api/atr.c`
- **pix_api_xreg()** (10 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/pix.c`
- **api_push_n()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **std_api_read_xram()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/api/std.c`
- **std_api_write_xram()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/api/std.c`
- **std_validate_fd()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/api/std.c`
- **api_pop_n()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **api_task()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- **dir_api_chmod()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- **dir_api_getlabel()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- **dir_api_readdir()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- **dir_api_seekdir()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- **dir_api_stat()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- **dir_api_utime()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- *... and 85 more nodes in this community*

## Relationships

- [[FatFS Internals]] (600 shared connections)
- [[RP2040 USB HCD]] (17 shared connections)
- [[RIA API & Audio]] (15 shared connections)
- [[BLE HID/HCI Stack]] (14 shared connections)
- [[FatFS & Config Core]] (6 shared connections)
- [[VGA Core Runtime]] (5 shared connections)
- [[VGA Mode4 Affine Transform]] (3 shared connections)
- [[TCP/IP Network Stack]] (2 shared connections)
- [[NTP Time Service]] (1 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- `raw/github/picocomputer/rp6502/src/ria/api/atr.c`
- `raw/github/picocomputer/rp6502/src/ria/api/clk.c`
- `raw/github/picocomputer/rp6502/src/ria/api/dir.c`
- `raw/github/picocomputer/rp6502/src/ria/api/pro.c`
- `raw/github/picocomputer/rp6502/src/ria/api/std.c`
- `raw/github/picocomputer/rp6502/src/ria/main.c`
- `raw/github/picocomputer/rp6502/src/ria/str/rln.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/com.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/com.h`
- `raw/github/picocomputer/rp6502/src/ria/sys/cpu.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/pix.c`

## Audit Trail

- EXTRACTED: 271 (41%)
- INFERRED: 394 (59%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*