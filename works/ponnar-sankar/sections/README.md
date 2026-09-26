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
- Part002 body leakage at Part001 closure — **0**
- canonical Part001 page mutations caused by assembly — **0**
- scan16 — **image-backed map plate preserved as `../assets/scan-0016-map.png`; no Unicode map-label reconstruction**
- outgoing **75→76** — **GENUINE CONTINUATION / AUDITED / PASS**
- validation — `../PART_001_ASSEMBLED_TAMIL_VALIDATION.md`
- Part001 assembled layer remains **FINAL CLOSED / FROZEN**

### Part002 — ASSEMBLED TAMIL VERIFIED / PASS / CLOSED

- physical coverage — **scans76–145**
- canonical records represented — **70/70**
- assembled files — **8/8 VERIFIED**
- missing / duplicate canonical coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- audit/control-note leakage into literary text — **0**
- canonical Part002 page mutations caused by assembly — **0**
- frozen Part001 section mutations caused by Part002 assembly — **0**
- Part003 body leakage — **0**
- incoming **75→76** — **GENUINE CONTINUATION / AUDITED / PASS**
- outgoing **145→146** — **PENDING Part003 direct witness**
- validation — `../PART_002_ASSEMBLED_TAMIL_VALIDATION.md`

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
| 8 | 001 | `08-unmaiyin-uthayam.md` | 70–75 | chapter7 `உண்மையின் உதயம்`; frozen Part001 segment | **VERIFIED** |
| 9 | 002 | `09-unmaiyin-uthayam-part002-continuation.md` | 76–80 | chapter7 continuation only; no synthesized opener heading | **VERIFIED** |
| 10 | 002 | `10-karagam-vidum-thiruvizha.md` | 81–89 | chapter8 `கரகம் விடும் திருவிழா` | **VERIFIED** |
| 11 | 002 | `11-maniyangurichchi-kurinji-maangal.md` | 90–98 | chapter9 `மணியங்குறிச்சி குறிஞ்சி மான்கள்` | **VERIFIED** |
| 12 | 002 | `12-archchanai-yaar-vayirukku.md` | 99–108 | chapter10 `அர்ச்சனை- யார் வயிறுக்கு?` | **VERIFIED** |
| 13 | 002 | `13-aasaiyil-arukkaani-thangam.md` | 109–118 | chapter11 `ஆசையில் அருக்காணித் தங்கம்` | **VERIFIED** |
| 14 | 002 | `14-poonaiyil-porkkolam.md` | 119–127 | chapter12 `பூனையில் போர்க்கோலம்` | **VERIFIED** |
| 15 | 002 | `15-vazhiyil-vandha-vibareetham.md` | 128–137 | chapter13 `வழியில் வந்த விபரீதம்` | **VERIFIED** |
| 16 | 002 | `16-raachchaandaar-malai-nokki.md` | 138–145 | chapter14 `ராச்சாண்டார் மலைநோக்கி...`; Part002 split edge | **VERIFIED** |

## Assembly rules

1. Literary body text comes only from each verified canonical page's `## Source transcription` block.
2. Source-visible chapter number/title display headings are retained once from the corresponding verified canonical opener record; no title wording is supplied from outside `pages/`.
3. Cross-Part continuations do not synthesize a second chapter opener. Part002 scans76–80 therefore continue chapter7 without inventing a new displayed chapter number/title.
4. Preserve source spelling, punctuation, paragraph/dialogue order, displayed text and historical forms.
5. Preserve physical-page provenance with non-rendering HTML boundary comments; these comments are control provenance and are excluded from literary text.
6. Blank scans and image-only structures remain represented without invented printed text.
7. Exclude Pass/review/audit notes, canonical YAML, running headers, printed-page furniture, copy marks and other control metadata from literary text.
8. Canonical `pages/` always govern; this reading layer never authorizes silent correction of canonical Tamil.
9. Do not import next-Part body text across an unresolved outgoing split boundary.

## Boundary safeguards

### Part001 → Part002

- **75→76 — GENUINE CONTINUATION / AUDITED / PASS**
- frozen Part001 `08-unmaiyin-uthayam.md` remains scans70–75
- Part002 continuation is held separately in `09-unmaiyin-uthayam-part002-continuation.md`
- no mutation of the frozen Part001 assembled file was required

### Part002 → Part003

- outgoing **145→146 — PENDING Part003 direct witness**
- scan145 remains terminal for the current assembled Part002 layer
- no scan146 / Part003 wording is present or inferred

Part001 assembled Tamil remains **FINAL CLOSED / FROZEN**.

Part002 assembled Tamil is **VERIFIED / PASS / CLOSED**.

Part002 is **FINAL CLOSED / FROZEN**. Canonical Tamil, assembled Tamil and maintained English are frozen.

Exact next activity: **Part003 source intake when source is supplied; directly audit 145→146 before Pass1**.
