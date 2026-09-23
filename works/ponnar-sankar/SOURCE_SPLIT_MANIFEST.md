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
| 001 | yes | `TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_001_pages_1-75.pdf` | 49648830 | `7c18dcd38e4710962da5f31391f3bd74ce73046f2aeceda97e6cb5d8e1b65ae6` | 75 | 1–75 | **REGISTERED / COMPLETE** | NOT STARTED |
| 002 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 003 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 004 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 005 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 006 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 007 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |
| 008 | pending | — | — | — | — | — | NOT REGISTERED | NOT STARTED |

## Current accounting

- registered Parts: **1/8**
- registered physical scan coverage: **1–75 / 75 scans**
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
- Part001 English complete translated/source-checked: **5/9 / 5/9**
- Part001 English partial: **E6 scans43–45 drafted + checked; scans46–51 pending**
- English physical processing coverage: **scans1–45 / 45 of 75**
- English cadence: **15 physical scans per iteration**
- Part002–Part008: **pending source intake**
- outgoing Part001 boundary **75→76**: **PENDING Part002 witness**

## Current frontier

**English scans46–60 — finish E6, complete E7 — next activity.**
