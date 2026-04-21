---
type: "query"
date: "2026-04-21T05:16:03.338456+00:00"
question: "Why does RP6502 Interface Adapter (RIA) bridge 6502/RIA core to VGA/PIX, RIA-W, and XRAM/memory maps?"
contributor: "graphify"
source_nodes: ["RP6502 Interface Adapter (RIA)", "RP6502 Video Graphics Array (firmware module)", "RIA memory mapping"]
---

# Q: Why does RP6502 Interface Adapter (RIA) bridge 6502/RIA core to VGA/PIX, RIA-W, and XRAM/memory maps?

## Answer

BFS from node rp6502_ria_picocomputer_documentation_ria: RIA sits in community 2 (6502 platform). Hop-1 EXTRACTED edges tie it to the platform (Pico 2 RIA hardware, 65C02, Picocomputer 6502, RP6502-OS), to VGA firmware (conceptually_related_to, RP6502-VGA doc), to RIA-W (semantically_similar_to INFERRED), and to RIA memory mapping (references) which links into community 4. Hop-2 from VGA reaches PIX bus, XRAM (shares_data_with EXTRACTED), monitor, and U4 VGA Pico—community 0. Hyperedge in graph.json groups PIX, XRAM, and VGA PIX device 1. RIA-W neighbor chains stay in community 3 for Wi-Fi/BT/modem features. High betweenness is structural: RIA is the documented hub that ties optional modules (VGA, RIA-W, OS) and memory/PIX semantics in one doc set.

## Source Nodes

- RP6502 Interface Adapter (RIA)
- RP6502 Video Graphics Array (firmware module)
- RIA memory mapping