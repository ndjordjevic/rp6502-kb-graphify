# Build System & Modules

> 14 nodes · cohesion 0.16

## Key Concepts

- **VGA executable target, sources, and tinyusb_device link** (4 connections) — `raw/github/picocomputer/rp6502/src/vga/CMakeLists.txt`
- **COM ring buffers, ANSI replies, and USB CDC terminal integration** (4 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/com.c`
- **RIA PIO backchannel UART and handshake with host COM** (4 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/ria.c`
- **VGA scanvideo timing, planes, and display mode switching** (4 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/vga.c`
- **Root CMake: Pico SDK, bundled TinyUSB path, RIA and VGA subprojects** (3 connections) — `raw/github/picocomputer/rp6502/CMakeLists.txt`
- **RP2040 native USB host controller driver for TinyUSB HCD** (2 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- **RP2040 TinyUSB hardware init, locks, and DPRAM-safe memcpy** (2 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/rp2040_usb.c`
- **RIA/RIA-W board-selected firmware target and sources** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/CMakeLists.txt`
- **COM subsystem public declarations** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/com.h`
- **TinyUSB MSC host class driver and SCSI-style status handling** (1 connections) — `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- **Pixel framebuffer and blit-related declarations** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/pix.h`
- **Picocomputer 6502 firmware family, releases, and developer setup** (1 connections) — `raw/github/picocomputer/rp6502/README.md`
- **System helpers and version string exposure** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/sys.h`
- **VGA subsystem public declarations** (1 connections) — `raw/github/picocomputer/rp6502/src/vga/sys/vga.h`

## Relationships

- [[Network Services & Help]] (30 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/CMakeLists.txt`
- `raw/github/picocomputer/rp6502/README.md`
- `raw/github/picocomputer/rp6502/src/ria/CMakeLists.txt`
- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/hcd_rp2040.c`
- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/msc_host.c`
- `raw/github/picocomputer/rp6502/src/tinyusb_rp6502/rp2040_usb.c`
- `raw/github/picocomputer/rp6502/src/vga/CMakeLists.txt`
- `raw/github/picocomputer/rp6502/src/vga/sys/com.c`
- `raw/github/picocomputer/rp6502/src/vga/sys/com.h`
- `raw/github/picocomputer/rp6502/src/vga/sys/pix.h`
- `raw/github/picocomputer/rp6502/src/vga/sys/ria.c`
- `raw/github/picocomputer/rp6502/src/vga/sys/sys.h`
- `raw/github/picocomputer/rp6502/src/vga/sys/vga.c`
- `raw/github/picocomputer/rp6502/src/vga/sys/vga.h`

## Audit Trail

- EXTRACTED: 14 (47%)
- INFERRED: 16 (53%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*