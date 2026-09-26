# பொன்னர் சங்கர் — Source Split Manifest

## Rules

- Exactly **8 user-supplied split PDFs** are expected.
- Split order determines **Part001–Part008**.
- Splits are size-based; page counts are not presumed equal.
- A row is populated only from the controlling supplied file.
- `scan_page` ranges are cumulative and continuous across Parts.
- Source PDFs remain outside Git.

| Part | Supplied | Exact filename | Bytes | SHA-256 | Local PDF pages | Global scans | Intake | Final closure |
|---:|---|---|---:|---|---:|---|---|---|
| 001 | yes | `TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_001_pages_1-75.pdf` | 49648830 | `7c18dcd38e4710962da5f31391f3bd74ce73046f2aeceda97e6cb5d8e1b65ae6` | 75 | 1–75 | **REGISTERED / COMPLETE** | **FINAL CLOSED / FROZEN** |
| 002 | yes | `TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_002_pages_76-145.pdf` | 49532734 | `d6bfca1bb53a21c72e4eab0ca03db545c9cf7070cd3e2cf8eaca9d864596c6cd` | 70 | 76–145 | **REGISTERED / COMPLETE** | **PASS1 COMPLETE / PASS — PASS2A CLOSED / COMPLETE / PASS 70/70 — PASS2B CLOSED / COMPLETE / PASS 70/70 — PASS3 IN PROGRESS 30/70** |
| 003 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 004 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 005 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 006 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 007 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 008 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |

## Current accounting

- registered Parts: **2/8**
- registered physical scan coverage: **1–145 / 145 scans**
- Part001 source intake: **REGISTERED / COMPLETE**
- Part001 canonical records: **75/75 — scans1–75**
- Part001 Pass 1: **COMPLETE — 75/75 canonical; 74 textual pages + 1 image-map page**
- Part001 Pass 1 pending physical scans: **0/75**
- unresolved Pass1 source-reading holds: **0**
- Part001 Pass 2A: **COMPLETE — 75/75 reviewed; 31 corrections recorded; 0 unresolved**
- Part001 Pass 2B: **COMPLETE / PASS — 75/75 reviewed; 8 corrections; 0 unresolved**
- Part001 Pass 3: **COMPLETE / PASS — 75/75 reviewed; 0 structural corrections; 0 unresolved**
- Part001 whole-Part audit: **PASS / COMPLETE — 0 blockers**
- Part001 final metadata/status synchronization: **COMPLETE — 75/75 status verified / 75/75 visual verified**
- Part001 Tamil archival-ready: **PASS / COMPLETE**
- durable Tamil archival-ready checkpoint: `PART_001_TAMIL_ARCHIVAL_READY.md`
- Part001 assembled Tamil: **VERIFIED / PASS / CLOSED — 9/9 section files / exact canonical coverage 75/75**
- Part001 assembled audit: **0 missing / 0 duplicate / 0 unsupported Tamil / 0 control-note leakage / 0 canonical page mutations / 0 Part002 body leakage**
- durable assembled-Tamil validation: `PART_001_ASSEMBLED_TAMIL_VALIDATION.md`
- Part001 English planning/setup: **COMPLETE / PASS — E1–E9 reserved**
- Part001 English complete translated/source-checked: **9/9 / 9/9**
- Part001 English partial: **0**
- English physical processing coverage: **scans1–75 / 75 of 75**
- latest user-directed page iteration: **30 scans / scans46–75**
- whole-Part glossary reconciliation: **RECONCILED / PASS**
- glossary reconciliation English section edits: **0**
- unresolved glossary holds: **0**
- English editorial review: **PASS / CLOSED**
- whole-Part bilingual review: **PASS / CLOSED**
- release/readiness: **PASS / CLOSED**
- unresolved release/readiness blockers: **0**
- release-ready synchronization: **PASS / CLOSED**
- Part001 final closure: **PASS / CLOSED / FROZEN**
- Part002 source intake: **REGISTERED / COMPLETE — 70 pages / scans76–145**
- Part002 incoming 75→76: **GENUINE CONTINUATION / AUDITED / PASS**
- Part002 Pass1: **COMPLETE / PASS — 70/70 TEXT-COMPLETE — scans76–145**
- Part002 Pass1 pending: **0/70**
- Part002 Pass2A: **CLOSED / COMPLETE / PASS — 70/70 REVIEWED — scans76–145**
- Part002 Pass2A source-text corrections: **47**
- Part002 Pass2A pending: **0/70**
- Part002 Pass2B: **CLOSED / COMPLETE / PASS — 70/70 REVIEWED — scans76–145**
- Part002 Pass2B source-text corrections: **19**
- Part002 Pass2B pending: **0/70**
- Part002 Pass3: **IN PROGRESS — 30/70 REVIEWED / PASS — scans76–105**
- Part002 Pass3 structural corrections: **0**
- Part002 Pass3 unresolved visual / structural questions: **0**
- Part002 Pass3 pending: **40/70 — scans106–145**
- Part002 Pass3 cadence: **15 pages per iteration; final remainder may be smaller**
- Part002 Pass2B cadence: **10 scans per batch**
- Part003–Part008: **pending source intake**
- outgoing Part001 / incoming Part002 boundary **75→76**: **GENUINE CONTINUATION / AUDITED / PASS**
- outgoing Part002 boundary **145→146**: **PENDING Part003 witness**

## Current frontier

**Part002 Pass3 Batch3 — scans106–120 / local pages31–45 — next activity.**
