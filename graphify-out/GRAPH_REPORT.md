# Graph Report - ./raw/web  (2026-04-20)

## Corpus Check
- Corpus is ~39,947 words - fits in a single context window. You may not need a graph.

## Summary
- 47 nodes · 118 edges · 8 communities detected
- Extraction: 93% EXTRACTED · 7% INFERRED · 0% AMBIGUOUS · INFERRED: 8 edges (avg confidence: 0.88)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- [[_COMMUNITY_Interrupts and 65C02 ISR Patterns|Interrupts and 65C02 ISR Patterns]]
- [[_COMMUNITY_RP6502 Platform and Toolchain|RP6502 Platform and Toolchain]]
- [[_COMMUNITY_Comparison and Status Flags|Comparison and Status Flags]]
- [[_COMMUNITY_Hardware and Memory Layout|Hardware and Memory Layout]]
- [[_COMMUNITY_VGA, PIX Bus and Raspberry Pi Pico|VGA, PIX Bus and Raspberry Pi Pico]]
- [[_COMMUNITY_NMOS vs 65C02 Instruction Differences|NMOS vs 65C02 Instruction Differences]]
- [[_COMMUNITY_RP6502-OS API and XRAM|RP6502-OS API and XRAM]]
- [[_COMMUNITY_BCD Decimal Mode|BCD Decimal Mode]]

## God Nodes (most connected - your core abstractions)
1. `Web Clips README` - 15 edges
2. `RP6502-OS Documentation` - 10 edges
3. `65C02 Instruction Set Architecture` - 10 edges
4. `RP6502-RIA Documentation` - 9 edges
5. `RP6502-RIA Interface Adapter` - 9 edges
6. `Picocomputer 6502 — cc65 Documentation` - 8 edges
7. `Picocomputer 6502 Overview Documentation` - 8 edges
8. `Investigating Interrupts — 6502.org` - 8 edges
9. `Register Preservation Using The Stack — 6502.org` - 8 edges
10. `65C02 Opcodes Reference — 6502.org` - 8 edges

## Surprising Connections (you probably didn't know these)
- `Register Preservation Using The Stack — 6502.org` --semantically_similar_to--> `Investigating Interrupts — 6502.org`  [INFERRED] [semantically similar]
  raw/web/6502.org/Register Preservation Using The Stack — 6502.org.md → raw/web/6502.org/Investigating Interrupts — 6502.org.md
- `6502 Compare Instructions Tutorial — 6502.org` --semantically_similar_to--> `Beyond 8-bit Unsigned Comparisons — 6502.org`  [INFERRED] [semantically similar]
  raw/web/6502.org/6502 Compare Instructions — 6502.org.md → raw/web/6502.org/Beyond 8-bit Unsigned Comparisons — 6502.org.md
- `65C02 Opcodes Reference — 6502.org` --semantically_similar_to--> `NMOS 6502 Opcodes Reference — 6502.org`  [INFERRED] [semantically similar]
  raw/web/6502.org/65C02 Opcodes — 6502.org.md → raw/web/6502.org/NMOS 6502 Opcodes — 6502.org.md
- `The Overflow (V) Flag Explained — 6502.org` --semantically_similar_to--> `Beyond 8-bit Unsigned Comparisons — 6502.org`  [INFERRED] [semantically similar]
  raw/web/6502.org/The Overflow (V) Flag Explained — 6502.org.md → raw/web/6502.org/Beyond 8-bit Unsigned Comparisons — 6502.org.md
- `RP6502-RIA Interface Adapter` --semantically_similar_to--> `RP6502-RIA-W (WiFi Variant)`  [INFERRED] [semantically similar]
  raw/web/picocomputer.github.io/RP6502-RIA — Picocomputer  documentation.md → raw/web/picocomputer.github.io/RP6502-RIA-W — Picocomputer  documentation.md

## Hyperedges (group relationships)
- **Picocomputer 6502 Core Hardware Platform** — concept_w65c02s, concept_w65c22s, concept_rp6502ria [EXTRACTED 0.98]
- **PIX Bus / XRAM / RP6502-VGA Video Data Pipeline** — concept_pix_bus, concept_xram, concept_rp6502vga [EXTRACTED 0.97]
- **RP6502 Programming Environment (cc65 + llvm-mos + RP6502-OS)** — concept_cc65, concept_llvm_mos, concept_rp6502os [INFERRED 0.88]

## Communities

### Community 0 - "Interrupts and 65C02 ISR Patterns"
Cohesion: 0.38
Nodes (10): 65C02 Instruction Set Architecture, 6502 Interrupt Handling (IRQ/NMI/BRK), PHX/PHY/PLX/PLY Instructions (65C02 stack push/pull X/Y), Stack-Based Register Preservation, WAI Instruction (65C02 ultra-fast interrupt response), Investigating Interrupts — 6502.org, Rationale: 65C02 clears D flag on interrupt (6502 does not), Rationale: PHX/PHY simplify ISR register preservation vs 6502 workarounds (+2 more)

### Community 1 - "RP6502 Platform and Toolchain"
Cohesion: 0.52
Nodes (7): cc65 Compiler Toolchain, llvm-mos Compiler Toolchain, RP6502-OS Operating System, RP6502-RIA Interface Adapter, RP6502-RIA-W (WiFi Variant), Picocomputer 6502 Overview Documentation, RP6502-RIA-W Documentation

### Community 2 - "Comparison and Status Flags"
Cohesion: 0.67
Nodes (6): Beyond 8-bit Unsigned Comparisons — 6502.org, 6502 Compare Instructions Tutorial — 6502.org, 6502 Compare Instructions (CMP/CPX/CPY), Overflow (V) Flag, The Overflow (V) Flag Explained — 6502.org, Web Clips README

### Community 3 - "Hardware and Memory Layout"
Cohesion: 0.47
Nodes (6): Picocomputer 6502 — cc65 Documentation, RP6502 Memory Layout, W65C02S CPU, W65C22S VIA (Versatile Interface Adapter), Picocomputer 6502 Hardware Documentation, Rationale: No ROM in 6502 address space (RP6502 loads to RAM)

### Community 4 - "VGA, PIX Bus and Raspberry Pi Pico"
Cohesion: 0.47
Nodes (6): Raspberry Pi Pico 2, PIX Bus (Pico Information Exchange), RP6502-VGA Video Modes (Console/Character/Tile/Bitmap/Sprite), Rationale: PIX Bus created due to limited Pico GPIO pins, RP6502-RIA Documentation, RP6502-VGA Documentation

### Community 5 - "NMOS vs 65C02 Instruction Differences"
Cohesion: 0.8
Nodes (5): 65C02 Opcodes Reference — 6502.org, JMP Indirect Bug (NMOS 6502 page-boundary), NMOS 6502 Instruction Set Architecture, NMOS 6502 Opcodes Reference — 6502.org, Rationale: 65C02 fixes JMP indirect page-boundary bug (costs 1 extra cycle)

### Community 6 - "RP6502-OS API and XRAM"
Cohesion: 0.6
Nodes (5): POSIX-like OS API (RP6502-OS ABI), RP6502-VGA Video Adapter, XRAM (Extended RAM, 64KB shared), Rationale: XRAM bulk I/O at 512 KB/sec eliminates need for paged memory, RP6502-OS Documentation

### Community 7 - "BCD Decimal Mode"
Cohesion: 1.0
Nodes (2): BCD Decimal Mode (D Flag, ADC/SBC), Decimal Mode (BCD) Tutorial — 6502.org

## Knowledge Gaps
- **1 isolated node(s):** `RP6502-VGA Video Modes (Console/Character/Tile/Bitmap/Sprite)`
  These have ≤1 connection - possible missing edges or undocumented components.
- **Thin community `BCD Decimal Mode`** (2 nodes): `BCD Decimal Mode (D Flag, ADC/SBC)`, `Decimal Mode (BCD) Tutorial — 6502.org`
  Too small to be a meaningful cluster - may be noise or needs more connections extracted.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `Web Clips README` connect `Comparison and Status Flags` to `Interrupts and 65C02 ISR Patterns`, `RP6502 Platform and Toolchain`, `Hardware and Memory Layout`, `VGA, PIX Bus and Raspberry Pi Pico`, `NMOS vs 65C02 Instruction Differences`, `RP6502-OS API and XRAM`, `BCD Decimal Mode`?**
  _High betweenness centrality (0.506) - this node is a cross-community bridge._
- **Why does `RP6502-OS Documentation` connect `RP6502-OS API and XRAM` to `RP6502 Platform and Toolchain`, `Comparison and Status Flags`, `Hardware and Memory Layout`?**
  _High betweenness centrality (0.137) - this node is a cross-community bridge._
- **Why does `Register Preservation Using The Stack — 6502.org` connect `Interrupts and 65C02 ISR Patterns` to `Comparison and Status Flags`, `NMOS vs 65C02 Instruction Differences`?**
  _High betweenness centrality (0.115) - this node is a cross-community bridge._
- **Are the 2 inferred relationships involving `RP6502-RIA Interface Adapter` (e.g. with `RP6502-RIA-W (WiFi Variant)` and `PIX Bus (Pico Information Exchange)`) actually correct?**
  _`RP6502-RIA Interface Adapter` has 2 INFERRED edges - model-reasoned connections that need verification._
- **What connects `RP6502-VGA Video Modes (Console/Character/Tile/Bitmap/Sprite)` to the rest of the system?**
  _1 weakly-connected nodes found - possible documentation gaps or missing edges._