# USB Host/Device Stack

> 82 nodes · cohesion 0.05

## Key Concepts

- **pad.c** (19 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **usb.c** (15 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/usb.c`
- **xin.c** (14 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- **DBG()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/usb.c`
- **DBG()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- **xin_class_driver_xfer_cb()** (8 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- **main_xreg()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/main.c`
- **mou_report()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/mou.c`
- **pad_distill_descriptor()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **pad_parse_report()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **hid.c** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/hid.c`
- **usb_init()** (7 connections) — `raw/github/picocomputer/rp6502/src/vga/usb/usb.c`
- **usb_status_response()** (7 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/usb.c`
- **pad_get_player_num()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **pad_report()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **pad_umount()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **mou.c** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/mou.c`
- **usb_task()** (6 connections) — `raw/github/picocomputer/rp6502/src/vga/usb/usb.c`
- **xin_class_driver_set_config()** (6 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- **hid_extract_bits()** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/hid.c`
- **DBG()** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- **tuh_hid_report_received_cb()** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/usb.c`
- **usb_idx_to_hid_slot()** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/usb.c`
- **xin_class_driver_close()** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- **xin_class_driver_open()** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- *... and 57 more nodes in this community*

## Relationships

- [[RIA Register Interface]] (312 shared connections)
- [[USB Mass Storage]] (11 shared connections)
- [[RIA API & Audio]] (4 shared connections)
- [[RP2040 USB HCD]] (3 shared connections)
- [[FatFS & Config Core]] (3 shared connections)
- [[FatFS Internals]] (1 shared connections)
- [[VGA Mode1 Graphics]] (1 shared connections)
- [[VGA Core Runtime]] (1 shared connections)
- [[TCP/IP Network Stack]] (1 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/hid/hid.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/hid.h`
- `raw/github/picocomputer/rp6502/src/ria/hid/kbd.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/mou.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/pad.c`
- `raw/github/picocomputer/rp6502/src/ria/hid/pad.h`
- `raw/github/picocomputer/rp6502/src/ria/main.c`
- `raw/github/picocomputer/rp6502/src/ria/usb/msc.c`
- `raw/github/picocomputer/rp6502/src/ria/usb/usb.c`
- `raw/github/picocomputer/rp6502/src/ria/usb/vcp.c`
- `raw/github/picocomputer/rp6502/src/ria/usb/xin.c`
- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- `raw/github/picocomputer/rp6502/src/vga/usb/cdc.c`
- `raw/github/picocomputer/rp6502/src/vga/usb/descriptors.c`
- `raw/github/picocomputer/rp6502/src/vga/usb/usb.c`

## Audit Trail

- EXTRACTED: 276 (81%)
- INFERRED: 63 (19%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*