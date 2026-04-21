# RIA Clock & Errno

> 9 nodes · cohesion 0.22

## Key Concepts

- **api_errno** (5 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **RIA fastcall xstack (pop/push/return)** (4 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- **CLK driver (real-time clock / timezone)** (2 connections) — `raw/github/picocomputer/rp6502/src/ria/api/clk.h`
- **api_errno_from_fatfs** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- **api_errno_from_lfs** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- **api_platform_errno** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- **Embedded TZ name / POSIX string table (CLK_TZINFO)** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/api/clk.c`
- **Directory and file management API** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/api/dir.h`
- **STDIO to 6502 (std_init/task/stop)** (1 connections) — `raw/github/picocomputer/rp6502/src/ria/api/std.h`

## Relationships

- [[NTP Time Service]] (16 shared connections)
- [[FatFS Internals]] (1 shared connections)

## Source Files

- `raw/github/picocomputer/rp6502/src/ria/api/api.c`
- `raw/github/picocomputer/rp6502/src/ria/api/api.h`
- `raw/github/picocomputer/rp6502/src/ria/api/clk.c`
- `raw/github/picocomputer/rp6502/src/ria/api/clk.h`
- `raw/github/picocomputer/rp6502/src/ria/api/dir.h`
- `raw/github/picocomputer/rp6502/src/ria/api/std.h`

## Audit Trail

- EXTRACTED: 10 (59%)
- INFERRED: 7 (41%)
- AMBIGUOUS: 0 (0%)

---

*Part of the graphify knowledge wiki. See [[index]] to navigate.*