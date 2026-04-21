# Network Services & Help

> 13 nodes · cohesion 0.19

## Key Concepts

- **CYW43 wireless radio driver (RF enable, country code, LED)** (4 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cyw.h`
- **SET command: PHI2, boot ROM, TZ, KB, VGA, NFC; on RIA-W RF/RFCC/SSID/PASS/BLE/PORT/KEY** (4 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/set.c`
- **BLE LE Central: btstack HIDS client, pairing, whitelist reconnect, HID reports to kbd/mou/pad** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- **AT command parser: classic Hayes plus modern +RF/+SSID and backslash net/tty settings** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/net/cmd.c`
- **HELP: flash tables for commands and SET attributes; optional extra responders** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/hlp.c`
- **Hayes AT modem emulator over telnet/TCP (states, phonebook, NVRAM, escape to command mode)** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/net/mdm.c`
- **RIA monitor: command dispatch, queued responses, pager, LFS/FatFS error mapping** (3 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- **Wi-Fi driver API: SSID/password, ready/connecting state** (2 connections) — `raw/github/picocomputer/rp6502/src/ria/net/wfi.h`
- **LittleFS-backed hal_flash_bank for BLE TLV persistence (replaces SDK two-sector flash)** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/net/ble_tlv.c`
- **lwIP TCP layer: DNS, connect, listen, pbuf RX ring, keepalive, mdm hook on connect** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/net/net.c`
- **6502 RAM and extended XRAM: hex dump, Intel HEX, binary upload with CRC** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/ram.c`
- **ROM *.rp6502 load/install: LFS+FAT, chunks to RIA/XRAM, assets, boot, ROM: stdio** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- **Telnet protocol and console server (wraps net connections)** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/net/tel.h`

## Relationships

- [[VGA File Structure]] (30 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/mon/hlp.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/mon.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/ram.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/rom.c`
- `raw/github/picocomputer/rp6502/src/ria/mon/set.c`
- `raw/github/picocomputer/rp6502/src/ria/net/ble.c`
- `raw/github/picocomputer/rp6502/src/ria/net/ble_tlv.c`
- `raw/github/picocomputer/rp6502/src/ria/net/cmd.c`
- `raw/github/picocomputer/rp6502/src/ria/net/cyw.h`
- `raw/github/picocomputer/rp6502/src/ria/net/mdm.c`
- `raw/github/picocomputer/rp6502/src/ria/net/net.c`
- `raw/github/picocomputer/rp6502/src/ria/net/tel.h`
- `raw/github/picocomputer/rp6502/src/ria/net/wfi.h`

## Audit Trail

- EXTRACTED: 26 (87%)
- INFERRED: 4 (13%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*