# Project Handover — Kalaignar Novels Archive 3

## Repository

- Repository: `pugazg/kalaignar-novels-3`
- Branch: `main`
- **LIVE MAIN IS AUTHORITATIVE.**
- Active work: `works/ponnar-sankar/`

## Work

- title: **பொன்னர் சங்கர்**
- author: **கலைஞர் மு. கருணாநிதி**
- supplied-source design: **8 split PDF files**, each <= **50 MB**
- split basis: **file size**, not a fixed page count
- source family / archive identifier: **pending first supplied split**
- total physical scan count: **pending intake**
- source PDFs remain outside Git

## Canonical numbering rule

- Parts are numbered by supplied split order: **Part001–Part008**
- `part_page` resets inside each split
- canonical `scan_page` is a single continuous physical-scan sequence across the entire work and **never resets**
- no Part scan range is guessed in advance
- each Part range is registered only after direct intake of that PDF
- printed pagination is recorded exactly as source-visible and may differ from physical scan numbering

## Mandatory Part lock

> **Finish the complete maintained workflow for the active Part before beginning canonical transcription of the next Part.**

Adjacent next-Part scans may be inspected only as boundary witnesses. No next-Part body text may leak into the active Part.

## Current state

- repository controls — **INITIALIZED**
- Part001–Part008 manifest — **CREATED / all pending intake**
- Part001 source intake — **NEXT**
- canonical page records — **0**
- verified pages — **0**
- assembled Tamil — **NOT STARTED**
- English — **BLOCKED pending Tamil closure**
- unresolved source-reading holds — **0 recorded because transcription has not started**

## Exact next activity

When Part001 is supplied:

1. register exact filename, bytes and SHA-256;
2. determine local physical PDF page count;
3. register Part001 global `scan_page` range beginning at scan 1;
4. identify source family / archive identifier from the controlling source where available;
5. record whether a usable text layer exists, while treating rendered source pixels as controlling authority;
6. create Part001 source-intake control;
7. begin **Pass 1** only after intake is complete.

Do not pre-register Part002 scan numbers until Part001 physical extent is known.
