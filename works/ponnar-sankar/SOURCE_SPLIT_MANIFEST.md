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
- Part002–Part008: **pending source intake**
- outgoing Part001 boundary **75→76**: **PENDING Part002 witness**

## Current frontier

**Part001 final metadata/status synchronization — Part audit PASS / COMPLETE; promote canonical records to verified without Tamil changes.**
