# Part 001 — Assembled Tamil Validation — பொன்னர் சங்கர்

## Result

**PART001 ASSEMBLED TAMIL — VERIFIED / PASS / CLOSED**

This validation audits the maintained Part001 Tamil reading layer under `sections/` against the already-verified canonical `pages/` records.

Pre-assembly live-main checkpoint:

`08e6c2ff9459d94ec9a8bcf870740845fb5042f4`

Section-construction endpoint before validation/control synchronization:

`627353a66e13e871429705b2cc17cac91abb7e20`

No OCR, web text, alternate edition or remembered wording was used to construct the assembled Tamil.

## Maintained convention

The live repository declares the Paayum Puli part-by-part workflow as its maintained model. Assembly therefore uses:

- `sections/` as the source-faithful readable Tamil layer;
- per-section YAML provenance;
- `layer: "assembled-reading"`;
- verified canonical `pages/` as the controlling Tamil authority;
- non-rendering HTML comments only for physical-source provenance;
- a durable `PART_001_ASSEMBLED_TAMIL_VALIDATION.md` gate record.

HTML provenance comments and YAML are not literary text and are excluded from readable-text comparison.

## Inventory gate

- assembled files — **9/9**
- assembled status — **verified on 9/9**
- represented physical scans — **1–75**
- canonical Part001 records represented — **75/75**
- missing canonical coverage — **0**
- duplicate canonical coverage — **0**
- Part002 body records represented — **0**

Section inventory:

1. `sections/00-front-matter.md` — scans1–7
2. `sections/01-nuzhaivaayil.md` — scans8–17
3. `sections/02-manavizhaavil-masachchaami.md` — scans18–25
4. `sections/03-virundhinar-vidudiyum-vedhanai-kottadiyum.md` — scans26–33
5. `sections/04-magizhchchiyum-marutchiyum.md` — scans34–42
6. `sections/05-iniya-soozhalum-puthiya-sogamum.md` — scans43–51
7. `sections/06-thaamarai-naachchiyin-sapatham.md` — scans52–60
8. `sections/07-peyar-sollaap-pattanam.md` — scans61–69
9. `sections/08-unmaiyin-uthayam.md` — scans70–75

## Canonical derivation audit

Each assembled file was fetched back from live `main` and reconstructed independently from the corresponding verified canonical page records.

For ordinary textual scans, only the canonical `## Source transcription` block was admitted as literary body text.

The current Ponnar Sankar canonical record layout stores the source-visible `நுழைவாயில்` and chapter number/title display headings immediately above `## Source transcription`. Those opener headings were retained once from the verified canonical opener records themselves. No heading wording was supplied from OCR, memory, the web or another edition.

Direct reconstructed-file comparisons:

| Assembled file | Canonical scans | Result |
|---|---:|---|
| `00-front-matter.md` | 1–7 | **EXACT / PASS** |
| `01-nuzhaivaayil.md` | 8–17 | **EXACT / PASS** |
| `02-manavizhaavil-masachchaami.md` | 18–25 | **EXACT / PASS** |
| `03-virundhinar-vidudiyum-vedhanai-kottadiyum.md` | 26–33 | **EXACT / PASS** |
| `04-magizhchchiyum-marutchiyum.md` | 34–42 | **EXACT / PASS** |
| `05-iniya-soozhalum-puthiya-sogamum.md` | 43–51 | **EXACT / PASS** |
| `06-thaamarai-naachchiyin-sapatham.md` | 52–60 | **EXACT / PASS** |
| `07-peyar-sollaap-pattanam.md` | 61–69 | **EXACT / PASS** |
| `08-unmaiyin-uthayam.md` | 70–75 | **EXACT / PASS** |

Unsupported Tamil insertion detected — **0**.

Pass/review/audit/control-note leakage into assembled literary text — **0**.

## Authoritative title gate

The assembled layer retains exactly the user-confirmed, verified canonical Part001 chapter titles:

1. `மணவிழாவில் மசச்சாமி`
2. `விருந்தினர் விடுதியும் வேதனை கொட்டடியும்`
3. `மகிழ்ச்சியும் மருட்சியும்`
4. `இனிய சூழலும் புதிய சோகமும்`
5. `தாமரை நாச்சியின் சபதம்`
6. `பெயர் சொல்லாப் பட்டணம்`
7. `உண்மையின் உதயம்`

Earlier superseded title readings were not reintroduced.

## Structural / non-text gate

All physical records remain accounted for in source order.

- scans5 and7 — intentional blank front-matter pages; represented structurally with no invented printed text;
- scan16 — image-backed map plate retained in `01-nuzhaivaayil.md` through `../assets/scan-0016-map.png`;
- scan16 Unicode map-label reconstruction — **0**;
- scan17 — blank map reverse/show-through page; represented structurally with no invented printed text;
- chapter ranges remain **18–25 / 26–33 / 34–42 / 43–51 / 52–60 / 61–69 / 70–75**.

## Canonical-integrity gate

A recursive Git-tree comparison was performed between the pre-assembly tree and the section-construction endpoint.

- canonical page blobs before assembly — **75**
- canonical page blobs after assembly — **75**
- canonical page additions/deletions — **0**
- canonical page blob mutations caused by assembly — **0**
- canonical Tamil wording mutations caused by assembly — **0**
- canonical status mutations caused by assembly — **0**

Canonical `pages/` remain authoritative.

## Outgoing boundary gate

Part001 scan75 retains its verified terminal text ending:

`ஆனால் அந்த மகிழ்ச்சி நீடிக்கவில்லை!”`

Outgoing **75→76** remains **PENDING Part002 direct witness**.

- scan76 / Part002 body text imported — **0**
- unsupported reconstruction across 75→76 — **0**
- Part002 canonical transcription begun — **NO**

## Required closure accounting

- exact canonical coverage — **75/75**
- missing coverage — **0**
- duplicate coverage — **0**
- unsupported Tamil insertion — **0**
- audit/control-note leakage into literary text — **0**
- canonical page mutations caused by assembly — **0**
- next-Part body leakage — **0**
- unresolved assembled-Tamil blockers — **0**

## Decision

**ASSEMBLED TAMIL MASTER — VERIFIED / PASS / CLOSED**

Part001 assembled Tamil is closed and frozen under **PART001 FINAL CLOSURE — PASS / CLOSED / FROZEN**. All downstream English, bilingual, release/readiness and release-ready synchronization gates are closed.

## Exact next activity

Part001 is **FINAL CLOSED / FROZEN**. When Part002 is supplied, perform source intake and direct **75→76** boundary audit before any Part002 canonical transcription.
