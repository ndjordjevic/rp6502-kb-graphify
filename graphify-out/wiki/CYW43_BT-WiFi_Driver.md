# CYW43 BT/WiFi Driver

> 16 nodes · cohesion 0.14

## Key Concepts

- **cyw_init** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **main_task** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **cyw_reset_radio** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **init** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **main** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **cyw_task** (2 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **ntp_task** (2 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ntp.c`
- **wfi_shutdown** (2 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- **ble_shutdown** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble.h`
- **BTstack BLE HID client toggles** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/btstack_config.h`
- **CYW43 firmware flash section** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/cyw43_config.h`
- **task** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **main_task** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/main.h`
- **TinyUSB host RHPORT0** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/tusb_config.h`
- **wfi_ready** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- **wfi_task** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`

## Relationships

- [[Build System & Modules]] (34 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/btstack_config.h`
- `raw/github/picocomputer/rp6502/src/ria/cyw43_config.h`
- `raw/github/picocomputer/rp6502/src/ria/main.c`
- `raw/github/picocomputer/rp6502/src/ria/main.h`
- `raw/github/picocomputer/rp6502/src/ria/net/ble.h`
- `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- `raw/github/picocomputer/rp6502/src/ria/net/ntp.c`
- `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- `raw/github/picocomputer/rp6502/src/ria/tusb_config.h`

## Audit Trail

- EXTRACTED: 24 (71%)
- INFERRED: 10 (29%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*