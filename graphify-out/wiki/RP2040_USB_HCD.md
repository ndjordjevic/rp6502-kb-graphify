# RP2040 USB HCD

> 67 nodes · cohesion 0.08

## Key Concepts

- **msc_host.c** (34 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **hcd_rp2040.c** (26 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **get_itf()** (22 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **get_epbuf()** (13 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **bot_xfer_cb()** (10 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **start_recovery()** (9 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **cbi_xfer_cb()** (8 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **complete_command()** (8 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **tuh_msc_scsi_sync()** (8 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **dpram_int_ep_buffer_ctrl()** (7 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **hcd_edpt_clear_stall()** (7 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **hcd_edpt_xfer()** (7 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **start_data_phase()** (7 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **edpt_find()** (6 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **__tusb_irq_path_func()** (6 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **is_bot()** (6 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **rp2040_usb.c** (6 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/rp2040_usb.c`
- **dpram_int_ep_ctrl()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **need_pre()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **bot_clear_for_csw_cb()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **cancel_inflight()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **cbi_adsc_complete()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **msch_close()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **msch_set_config()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **msch_xfer_cb()** (5 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- *... and 42 more nodes in this community*

## Relationships

- [[VGA Scanvideo PIO]] (215 shared connections)
- [[USB Mass Storage]] (122 shared connections)
- [[VGA Mode1 Graphics]] (4 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/rp2040_usb.c`

## Audit Trail

- EXTRACTED: 327 (96%)
- INFERRED: 14 (4%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*