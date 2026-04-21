# BLE HID/HCI Stack

> 125 nodes · cohesion 0.03

## Key Concepts

- **kbd.c** (24 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- **cfg_save_with_boot_opt()** (20 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/cfg.c`
- **cfg_load_with_boot_opt()** (19 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/cfg.c`
- **main_task()** (19 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **ble.c** (18 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- **cfg_save()** (16 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/cfg.c`
- **kbd_queue_key()** (15 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- **cyw.c** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **wfi.c** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- **cyw_get_rf_enable()** (11 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **kbd_rebuild_code_page_cache()** (10 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- **oem_request_code_page()** (10 connections) — `raw/github/picocomputer/rp6502/src/ria/api/oem.c`
- **ble_hids_client_handler()** (9 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- **oem.c** (9 connections) — `raw/github/picocomputer/rp6502/src/ria/api/oem.c`
- **kbd_report()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- **DBG()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- **cfg.c** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/sys/cfg.c`
- **ble_set_config()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- **cyw_reset_radio()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **cyw_set_rf_country_code()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- **HID keyboard driver** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.h`
- **kbd_init()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- **str_parse_uint8()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- **wfi_get_pass()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- **wfi_task()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- *... and 100 more nodes in this community*

## Relationships

- [[VGA Core Runtime]] (332 shared connections)
- [[RIA Register Interface]] (130 shared connections)
- [[FatFS & Config Core]] (28 shared connections)
- [[Network AT Commands]] (19 shared connections)
- [[RIA API & Audio]] (16 shared connections)
- [[RP2040 USB HCD]] (15 shared connections)
- [[TCP/IP Network Stack]] (10 shared connections)
- [[FatFS Internals]] (6 shared connections)
- [[VGA CDC Serial]] (5 shared connections)
- [[HID Keyboard/Mouse]] (1 shared connections)
- [[VGA Mode1 Graphics]] (1 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/fatfs/ff.c`
- `raw/github/picocomputer/rp6502/src/ria/api/clk.c`
- `raw/github/picocomputer/rp6502/src/ria/api/oem.c`
- `raw/github/picocomputer/rp6502/src/ria/api/oem.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd_de.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd_dk.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd_se.h`
- `raw/github/picocomputer/rp6502/src/ria/main.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/set.c`
- `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- `raw/github/picocomputer/rp6502/src/ria/net/cmd.c`
- `raw/github/picocomputer/rp6502/src/ria/net/cyw.c`
- `raw/github/picocomputer/rp6502/src/ria/net/tel.c`
- `raw/github/picocomputer/rp6502/src/ria/net/wfi.c`
- `raw/github/picocomputer/rp6502/src/ria/str/str.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/cfg.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/cpu.c`
- `raw/github/picocomputer/rp6502/src/ria/sys/led.c`

## Audit Trail

- EXTRACTED: 357 (63%)
- INFERRED: 209 (37%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*