# Assembled Tamil Reading Layer — பொன்னர் சங்கர்

This `sections/` directory is the maintained source-faithful Tamil reading layer derived only from verified canonical `../pages/` records.

Canonical `pages/` remain authoritative if any conflict is ever discovered.

## Closed Parts represented

### Part001 — ASSEMBLED TAMIL VERIFIED / PASS / CLOSED

- physical coverage — **scans1–75**
- canonical records represented — **75/75**
- assembled files — **9/9 VERIFIED**
- missing / duplicate canonical coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- audit/control-note leakage into literary text — **0**
- Part002 body leakage — **0**
- canonical Part001 page mutations caused by assembly — **0**
- scan16 — **image-backed map plate preserved as `../assets/scan-0016-map.png`; no Unicode map-label reconstruction**
- outgoing **75→76** — **PENDING Part002 direct witness**
- validation — `../PART_001_ASSEMBLED_TAMIL_VALIDATION.md`

## Section inventory

| Order | Part | File | Source scans | Source structure | Status |
|---:|---:|---|---:|---|---|
| 0 | 001 | `00-front-matter.md` | 1–7 | cover / title / publication details / preface / blanks / title divider | **VERIFIED** |
| 1 | 001 | `01-nuzhaivaayil.md` | 8–17 | `நுழைவாயில்`; scan16 image map; scan17 blank | **VERIFIED** |
| 2 | 001 | `02-manavizhaavil-masachchaami.md` | 18–25 | chapter1 `மணவிழாவில் மசச்சாமி` | **VERIFIED** |
| 3 | 001 | `03-virundhinar-vidudiyum-vedhanai-kottadiyum.md` | 26–33 | chapter2 `விருந்தினர் விடுதியும் வேதனை கொட்டடியும்` | **VERIFIED** |
| 4 | 001 | `04-magizhchchiyum-marutchiyum.md` | 34–42 | chapter3 `மகிழ்ச்சியும் மருட்சியும்` | **VERIFIED** |
| 5 | 001 | `05-iniya-soozhalum-puthiya-sogamum.md` | 43–51 | chapter4 `இனிய சூழலும் புதிய சோகமும்` | **VERIFIED** |
| 6 | 001 | `06-thaamarai-naachchiyin-sapatham.md` | 52–60 | chapter5 `தாமரை நாச்சியின் சபதம்` | **VERIFIED** |
| 7 | 001 | `07-peyar-sollaap-pattanam.md` | 61–69 | chapter6 `பெயர் சொல்லாப் பட்டணம்` | **VERIFIED** |
| 8 | 001 | `08-unmaiyin-uthayam.md` | 70–75 | chapter7 `உண்மையின் உதயம்`; Part001 terminal continuation | **VERIFIED** |

## Assembly rules

1. Literary body text comes only from each verified canonical page's `## Source transcription` block.
2. Source-visible `நுழைவாயில்` and chapter number/title display headings are retained once from the corresponding verified canonical opener record; no title wording is supplied from outside `pages/`.
3. Preserve source spelling, punctuation, paragraph/dialogue order, displayed text and historical forms.
4. Preserve physical-page provenance with non-rendering HTML boundary comments; these comments are control provenance and are excluded from the literary text.
5. Blank scans **5, 7 and 17** remain represented structurally without inventing printed text.
6. Scan16 remains a visual map asset in source order; its labels are not reconstructed as Unicode.
7. Exclude Pass/review/audit notes, canonical YAML, page furniture, copy marks and other control metadata from the literary text.
8. Canonical `pages/` always govern; this reading layer never authorizes silent correction of canonical Tamil.
9. Do not cross the Part001 outgoing boundary by importing or reconstructing Part002 body text.

## Part001 boundary safeguard

- incoming boundary — **NONE**
- outgoing **75→76** — **PENDING Part002 direct witness**
- scan75 remains terminal at `ஆனால் அந்த மகிழ்ச்சி நீடிக்கவில்லை!”`
- no scan76 / Part002 continuation is present in this assembled layer

Part001 assembled Tamil is **VERIFIED / PASS / CLOSED**.

Downstream English planning/setup is now **COMPLETE / PASS** with **E1–E9** reserved over scans1–75. No English literary prose was drafted during setup. Exact next gate: **E1 draft + source-check — front matter / scans1–7**.
