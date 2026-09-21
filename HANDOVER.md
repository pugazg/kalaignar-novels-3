# Project Handover — Kalaignar Novels Archive 3

## Repository

- Repository: `pugazg/kalaignar-novels-3`
- Branch: `main`
- **LIVE MAIN IS AUTHORITATIVE.**
- Active work: `works/ponnar-sankar/`

## Work

- title: **பொன்னர் சங்கர்**
- source-visible subtitle: **அண்ணன்மார் வரலாறு**
- author: **கலைஞர் மு. கருணாநிதி**
- supplied-source design: **8 split PDF files**, each <= **50 MB**
- split basis: **file size**, not a fixed page count
- source family / archive identifier: **TVA_BOK_0065560**
- total physical scan count: **pending intake of Parts002–008**
- source PDFs remain outside Git

## Canonical numbering rule

- Parts are numbered by supplied split order: **Part001–Part008**
- `part_page` resets inside each split
- canonical `scan_page` is a single continuous physical-scan sequence across the entire work and **never resets**
- no future Part scan range is guessed in advance
- each Part range is registered only after direct intake of that PDF
- printed pagination is recorded exactly as source-visible and may differ from physical scan numbering

## Mandatory Part lock

> **Finish the complete maintained workflow for the active Part before beginning canonical transcription of the next Part.**

Adjacent next-Part scans may be inspected only as boundary witnesses. No next-Part body text may leak into the active Part.

## Part001 — SOURCE INTAKE COMPLETE

- source: `TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_001_pages_1-75.pdf`
- bytes: **49,648,830**
- SHA-256: `7c18dcd38e4710962da5f31391f3bd74ce73046f2aeceda97e6cb5d8e1b65ae6`
- local pages: **75**
- global scans: **1–75**
- text layer: **absent / no usable parsed text exposed**
- controlling authority: **rendered source pixels**
- source-visible edition: **ஒன்பதாம் பதிப்பு 2017**
- source-visible publication month: **ஏப்ரல் 2017**
- incoming boundary: **NONE**
- outgoing 75→76: **PENDING Part002 direct witness**
- durable intake: `works/ponnar-sankar/SOURCE_INTAKE_PART_001.md`

## Current state

- repository controls — **INITIALIZED / SYNCHRONIZED**
- registered Parts — **1/8**
- Part001 source intake — **COMPLETE**
- Part001 canonical page records — **70/75 — scans1–70**
- Part001 Pass 1 — **IN PROGRESS / BATCHES 1–7 PHYSICAL CAPTURE COMPLETE**
- Part001 Pass 1 text-complete — **69/75 — scans1–15,17–70**
- Part001 Pass 1 pending physical scans — **5/75 — scans71–75**
- unresolved Pass1 source-reading holds — **1 — scan16 dense cartographic minor labels**
- verified pages — **0**
- assembled Tamil — **NOT STARTED**
- English — **BLOCKED pending Tamil closure**
- Parts002–Part008 — **not registered**

## Exact next activity

Begin **Part001 Pass 1 — global scans71–75 / local pages71–75** — the final Pass1 physical batch. Carry the scan16 cartographic-label hold forward for later direct reread.

Keep all created records at `status: "needs-review"` and `visual_fidelity: "needs-review"`. Do not begin Pass 2A until Pass1 covers all **75** scans. Keep **75→76** pending until Part002 is supplied.
