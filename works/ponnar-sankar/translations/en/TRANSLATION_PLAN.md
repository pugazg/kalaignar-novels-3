# English Translation Plan — பொன்னர் சங்கர் / Part001

Status: **PLANNING/SETUP COMPLETE / PASS**

This is the control plan for the project-created English translation of **Part001 only**.

No English literary prose was drafted in this setup gate.

## Authority hierarchy

1. `works/ponnar-sankar/pages/` — canonical verified Tamil; controlling authority.
2. `works/ponnar-sankar/sections/` — **VERIFIED / PASS / CLOSED — 9/9** assembled Tamil reading layer.
3. `works/ponnar-sankar/translations/en/` — derived project-created English only.

If English conflicts with Tamil, canonical Tamil governs.

No OCR, web text, alternate edition, remembered wording or published/standard English translation is an authority.

## Part001 Tamil source state

Part001 is closed through Tamil archival and assembly:

- canonical scans — **1–75**
- canonical Tamil records — **75/75 verified**
- visual fidelity — **75/75 verified**
- Pass1 / Pass2A / Pass2B / Pass3 — **COMPLETE / PASS**
- whole-Part audit — **PASS / COMPLETE / REVALIDATED**
- final metadata/status synchronization — **COMPLETE**
- Tamil archival-ready — **PASS / COMPLETE**
- assembled Tamil — **VERIFIED / PASS / CLOSED**
- assembled files — **9/9**
- assembled canonical coverage — **75/75**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- audit/control-note leakage into literary text — **0**
- canonical page mutations caused by assembly — **0**
- Part002 body leakage — **0**
- incoming boundary — **NONE**
- outgoing boundary — **75→76 PENDING Part002 direct witness**

No source PDF is reopened merely for English planning or drafting.

## Live batch-number collision check

Live `translations/en/` was inspected immediately before setup.

Confirmed:

- existing English source-check controls — **0**
- existing reserved E-batches — **0**
- existing translation plan / glossary / progress controls — **0**
- maintained English literary files — **0**
- maintained English section-order collisions in **0–8** — **0**

Therefore the authorized Part001 batch sequence is:

**E1–E9**

and the planned English section-order range is:

**0–8**.

## Translation objective

Produce readable English that remains reversible to the verified Part001 Tamil evidence.

Preserve:

- narrator and character agency;
- chronology and information-release order;
- rhetorical questions, repetition, exclamations, irony and emphatic phrasing;
- paragraph/dialogue/display structure where meaningful;
- source-visible front-matter, introductory and chapter structure;
- source-specific personal names, titles, kinship relations, offices, labels and place forms;
- source-sensitive historical and lexical forms without silent normalization;
- quotations, songs, verse and proverbial material only from verified project Tamil;
- the open Part001 ending at scan75 without importing or inferring scan76.

Do not add explanatory history, geography, biography, religion, politics, folklore or literary interpretation unless the Tamil source itself supplies it.

## Part001 assembled source structure

Part001 contains **9 verified assembled Tamil files**:

1. `00-front-matter.md` — scans1–7 — front matter;
2. `01-nuzhaivaayil.md` — scans8–17 — `நுழைவாயில்`, including scan16 image-backed map and scan17 blank;
3. `02-manavizhaavil-masachchaami.md` — scans18–25 — chapter1 `மணவிழாவில் மசச்சாமி`;
4. `03-virundhinar-vidudiyum-vedhanai-kottadiyum.md` — scans26–33 — chapter2 `விருந்தினர் விடுதியும் வேதனை கொட்டடியும்`;
5. `04-magizhchchiyum-marutchiyum.md` — scans34–42 — chapter3 `மகிழ்ச்சியும் மருட்சியும்`;
6. `05-iniya-soozhalum-puthiya-sogamum.md` — scans43–51 — chapter4 `இனிய சூழலும் புதிய சோகமும்`;
7. `06-thaamarai-naachchiyin-sapatham.md` — scans52–60 — chapter5 `தாமரை நாச்சியின் சபதம்`;
8. `07-peyar-sollaap-pattanam.md` — scans61–69 — chapter6 `பெயர் சொல்லாப் பட்டணம்`;
9. `08-unmaiyin-uthayam.md` — scans70–75 — chapter7 `உண்மையின் உதயம்`, continuing beyond Part001.

English preserves this order exactly.

## Planned English batches

| Batch | Tamil assembled file | Planned English file | Scans | Working English handling |
|---|---|---|---:|---|
| **E1** | `00-front-matter.md` | `sections/00-front-matter.md` | 1–7 | front matter / bibliographic and preface material |
| **E2** | `01-nuzhaivaayil.md` | `sections/01-entrance.md` | 8–17 | **Entrance** — provisional functional rendering of `நுழைவாயில்` |
| **E3** | `02-manavizhaavil-masachchaami.md` | `sections/02-masachchaami-at-the-wedding.md` | 18–25 | **Masachchaami at the Wedding** — source-facing transliteration retained |
| **E4** | `03-virundhinar-vidudiyum-vedhanai-kottadiyum.md` | `sections/03-the-guest-lodge-and-the-shed-of-suffering.md` | 26–33 | **The Guest Lodge and the Shed of Suffering** — provisional |
| **E5** | `04-magizhchchiyum-marutchiyum.md` | `sections/04-joy-and-bewilderment.md` | 34–42 | **Joy and Bewilderment** — provisional |
| **E6** | `05-iniya-soozhalum-puthiya-sogamum.md` | `sections/05-a-pleasant-setting-and-a-new-sorrow.md` | 43–51 | **A Pleasant Setting and a New Sorrow** — provisional |
| **E7** | `06-thaamarai-naachchiyin-sapatham.md` | `sections/06-thamarai-naachchis-vow.md` | 52–60 | **Thamarai Naachchi's Vow** — provisional |
| **E8** | `07-peyar-sollaap-pattanam.md` | `sections/07-the-town-not-to-be-named.md` | 61–69 | **The Town Not to Be Named** — provisional |
| **E9** | `08-unmaiyin-uthayam.md` | `sections/08-the-dawn-of-truth.md` | 70–75 | **The Dawn of Truth** — provisional; Part001 terminal continuation |

Working English titles may be refined only during explicit batch source-check/editorial control. The verified Tamil titles are never changed to enforce English style.

Each batch must close **draft + source-check** before the next batch is considered closed.

## Chapter-title lock

The controlling Tamil titles are exactly:

1. `மணவிழாவில் மசச்சாமி`
2. `விருந்தினர் விடுதியும் வேதனை கொட்டடியும்`
3. `மகிழ்ச்சியும் மருட்சியும்`
4. `இனிய சூழலும் புதிய சோகமும்`
5. `தாமரை நாச்சியின் சபதம்`
6. `பெயர் சொல்லாப் பட்டணம்`
7. `உண்மையின் உதயம்`

No earlier superseded repository title reading may re-enter English controls.

## Structural locks

### Front matter

- preserve title, subtitle, author/publisher and publication-detail distinctions;
- do not modernize bibliographic wording or silently reconcile edition statements;
- source-visible display structure may be rendered readably, but no Tamil content is omitted.

### Scan16 map

- scan16 is an image-backed/non-text map plate;
- English literary body for scan16 — **0**;
- map-label transcription/translation from outside evidence — **prohibited**;
- retain non-rendering provenance for the map's position in E2;
- a later explicit visual-caption policy may describe only what the verified project source already establishes.

### Blank physical scans

- scans5, 7 and17 remain structurally represented;
- invented English prose for blank space — **0**.

### Outgoing 75→76

- scan75 is the final Part001 physical scan and remains inside chapter7;
- verified terminal Tamil ends `ஆனால் அந்த மகிழ்ச்சி நீடிக்கவில்லை!”`;
- **75→76 = PENDING Part002 direct witness**;
- E9 translates through scan75 only;
- do not import, paraphrase, infer or semantically complete from Part002;
- retain a non-rendering pending-boundary provenance marker;
- the pending boundary is not to be silently upgraded during English work.

## Names, titles, kinship and source variants

`GLOSSARY.md` is the active Part001 glossary.

Rules:

- prefer conservative source-facing transliteration for personal names and source-specific labels;
- preserve honorific distinctions such as `நாச்சி` / `நாச்சியார்` by occurrence where meaningful;
- render kinship terms from immediate relationship context rather than assigning one English word globally;
- retain `கவுண்டர்` as a source-facing title/name element unless a specific sentence clearly requires another functional treatment;
- do not normalize occurrence-sensitive compounds, spacing variants or historical forms upstream merely to make English consistent;
- no external/official spelling replaces the project source form solely for familiarity.

## Ritual and culturally specific terminology

Where the Tamil itself makes the function clear, a minimal functional English rendering may be used.

Where a secure direct equivalent is not established by Part001 evidence, retain a source-facing transliteration and let the immediate sentence carry meaning.

Do not insert ethnographic, religious or historical explanations into literary prose.

Terms requiring active source-check discipline include `மொய்க்காளரி`, `அருகுமணம்`, `பாதபூசை`, `நலங்கிடுதல்`, `சீர்வரிசை`, `முகூர்த்தக் கால்`, `மங்கல நாண்`, `அருமைக்காரர்கள்` and other source-specific wedding/ritual vocabulary.

## Quotations, songs, verse and proverbs

- translate only from the verified assembled Tamil;
- preserve meaningful line/block structure;
- preserve quotation boundaries and speaker attribution;
- do not import remembered, published or web English versions;
- do not silently replace source proverb/song wording with a standard English equivalent if that loses source structure.

## Source-check standard

For every batch:

1. compare the draft against the verified assembled Tamil and, where needed, canonical page source-transcription blocks;
2. account for every literary paragraph/dialogue/display block;
3. preserve source order and structural provenance;
4. record omissions, duplicates, unsupported English insertions and unresolved holds explicitly;
5. require canonical Tamil edits caused by English = **0**;
6. require assembled Tamil edits caused by English = **0**;
7. require Part002 leakage = **0**;
8. preserve outgoing 75→76 pending classification unless separately resolved by direct adjacent-source audit;
9. create the durable `E#_SOURCE_CHECK.md` record only when that batch closes **SOURCE-CHECKED / COMPLETE**.

## Planned lifecycle after E9

After E1–E9 all close **SOURCE-CHECKED / COMPLETE**:

1. whole-Part glossary reconciliation;
2. English editorial review;
3. whole-Part bilingual review against verified Tamil;
4. release/readiness report;
5. release-ready synchronization;
6. no-post-release textual-drift verification;
7. Part001 final closure / freeze.

Part002 canonical transcription remains blocked until Part001 final closure.

## Planning gate result

**PART001 ENGLISH TRANSLATION PLANNING/SETUP — COMPLETE / PASS**

- reserved batches — **E1–E9 / 9**
- planned maintained English files — **9**
- complete source coverage — **scans1–75**
- missing planned source coverage — **0**
- duplicate planned source coverage — **0**
- batch-number collisions — **0**
- English section-order collisions — **0**
- translated files — **0/9**
- source-checked files — **0/9**
- unresolved planning holds — **0**
- English literary prose drafted in planning gate — **0**
- canonical Tamil edits caused by planning — **0**
- assembled Tamil edits caused by planning — **0**
- Part002 leakage — **0**

## Processing cadence and current checkpoint

User-set English processing cadence: **15 physical scans per iteration**.

Completed translation iterations:

### Iteration 1 — scans1–15

- E1 scans1–7 — **SOURCE-CHECKED / COMPLETE**
- E2 scans8–15 — **drafted + directly checked**
- physical scans processed — **15/15**

### Iteration 2 — scans16–30

- E2 scans16–17 — **completed; whole E2 SOURCE-CHECKED / COMPLETE**
- E3 scans18–25 — **SOURCE-CHECKED / COMPLETE**
- E4 scans26–30 — **drafted + directly checked / IN PROGRESS**
- E4 scans31–33 — **PENDING**
- physical scans processed this iteration — **15/15**
- cumulative physical English coverage — **scans1–30 / 30 of 75**
- complete translated/source-checked files — **3/9 / 3/9**
- partial translated files — **1**
- canonical / assembled Tamil edits caused by English — **0 / 0**
- Part002 leakage — **0**

The original E-batch boundaries remain authoritative; the 15-scan iteration cadence may stop inside a batch. A durable `E#_SOURCE_CHECK.md` is created only when the whole E-batch closes.

### Iteration 3 — scans31–45

- E4 scans31–33 — **completed; whole E4 SOURCE-CHECKED / COMPLETE**
- E5 scans34–42 — **SOURCE-CHECKED / COMPLETE**
- E6 scans43–45 — **drafted + directly checked / IN PROGRESS**
- E6 scans46–51 — **PENDING**
- physical scans processed this iteration — **15/15**
- cumulative physical English coverage — **scans1–45 / 45 of 75**
- complete translated/source-checked files — **5/9 / 5/9**
- partial translated files — **1**
- canonical / assembled Tamil edits caused by English — **0 / 0**
- Part002 leakage — **0**

## Exact next gate

Continue **scans46–60** under the 15-page cadence:

1. finish E6 scans46–51 and close E6;
2. process E7 scans52–60 and close E7.

That is exactly **15 scans**. Do not process scan61.
