# English Translation Plan — பொன்னர் சங்கர் / Part002

Status: **PART002 ENGLISH TRANSLATION PLANNING/SETUP — COMPLETE / PASS**

This is the control plan for the project-created English translation of **Part002 only**.

No Part002 English literary prose was drafted in this setup gate.

## Authority hierarchy

1. `works/ponnar-sankar/pages/` — canonical verified Tamil; controlling authority.
2. `works/ponnar-sankar/sections/` — verified Part002 assembled Tamil reading layer; **8/8 VERIFIED / PASS / CLOSED**.
3. frozen Part001 English under `works/ponnar-sankar/translations/en/` — continuity reference for already-established project English forms only; it does not override Part002 Tamil.
4. Part002 English files to be created under `works/ponnar-sankar/translations/en/sections/` — derived project-created English only.

If English conflicts with Tamil, canonical Tamil governs.

No OCR, web text, alternate edition, remembered wording or published/standard English translation is an authority.

## Part002 Tamil source state

- source — `TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_002_pages_76-145.pdf`
- source SHA-256 — `d6bfca1bb53a21c72e4eab0ca03db545c9cf7070cd3e2cf8eaca9d864596c6cd`
- global scans — **76–145**
- local pages — **1–70**
- canonical Tamil records — **70/70 verified**
- visual fidelity — **70/70 verified**
- Pass1 / Pass2A / Pass2B / Pass3 — **COMPLETE / PASS**
- whole-Part audit — **PASS / COMPLETE**
- final metadata/status synchronization — **PASS / COMPLETE**
- Tamil archival-ready — **PASS / COMPLETE**
- assembled Tamil — **VERIFIED / PASS / CLOSED**
- assembled files — **8/8**
- assembled canonical coverage — **70/70**
- missing / duplicate assembled coverage — **0 / 0**
- unsupported Tamil insertion — **0**
- canonical mutations caused by assembly — **0**
- frozen Part001 section mutations caused by assembly — **0**
- Part003 body leakage — **0**
- incoming 75→76 — **GENUINE CONTINUATION / AUDITED / PASS**
- outgoing 145→146 — **PENDING Part003 direct witness**

Durable Tamil closure records:

- `../../PART_002_AUDIT.md`
- `../../PART_002_TAMIL_ARCHIVAL_READY.md`
- `../../PART_002_ASSEMBLED_TAMIL_VALIDATION.md`

## Live batch-number / English-section collision check

Live `translations/en/` was inspected before Part002 setup.

Confirmed:

- Part001 E-batches **E1–E9** already exist and are **FINAL CLOSED / FROZEN**;
- Part001 English section orders **0–8** already exist and are frozen;
- Part002 source-check controls **E10–E17** — **0 existing**;
- Part002 planned English section orders **9–16** — **0 existing**;
- Part002 maintained English literary files — **0 existing**.

Therefore the reserved Part002 batch sequence is:

**E10–E17**

and the reserved English section-order range is:

**9–16**.

Batch-number collisions — **0**.  
English section-order collisions — **0**.

## Translation objective

Produce readable English that remains reversible to the verified Part002 Tamil evidence.

Preserve:

- narrator and character agency;
- chronology and information-release order;
- dialogue, rhetorical questions, repetition, humour, irony and emphatic phrasing;
- meaningful paragraph/display structure;
- source-specific personal names, titles, kinship relations, offices, labels and place forms;
- source-sensitive lexical/historical forms without silent upstream normalization;
- quotations, songs, verse and proverbial material only from verified project Tamil;
- the audited chapter7 continuation across 75→76 without rewriting frozen Part001 English;
- the open Part002 ending at scan145 without importing or inferring scan146.

Do not add explanatory history, geography, biography, religion, politics, folklore or literary interpretation unless the Tamil source itself supplies it.

## Part002 assembled source structure

Part002 contains **8 verified assembled Tamil files**:

1. `09-unmaiyin-uthayam-part002-continuation.md` — scans76–80 — chapter7 continuation;
2. `10-karagam-vidum-thiruvizha.md` — scans81–89 — chapter8 `கரகம் விடும் திருவிழா`;
3. `11-maniyangurichchi-kurinji-maangal.md` — scans90–98 — chapter9 `மணியங்குறிச்சி குறிஞ்சி மான்கள்`;
4. `12-archchanai-yaar-vayirukku.md` — scans99–108 — chapter10 `அர்ச்சனை- யார் வயிறுக்கு?`;
5. `13-aasaiyil-arukkaani-thangam.md` — scans109–118 — chapter11 `ஆசையில் அருக்காணித் தங்கம்`;
6. `14-poonaiyil-porkkolam.md` — scans119–127 — chapter12 `பூனையில் போர்க்கோலம்`;
7. `15-vazhiyil-vandha-vibareetham.md` — scans128–137 — chapter13 `வழியில் வந்த விபரீதம்`;
8. `16-raachchaandaar-malai-nokki.md` — scans138–145 — chapter14 `ராச்சாண்டார் மலைநோக்கி...`, continuing beyond the Part002 split.

English preserves this order exactly.

## Planned English batches

| Batch | Tamil assembled file | Planned English file | Scans | Planning handling |
|---|---|---|---:|---|
| **E10** | `09-unmaiyin-uthayam-part002-continuation.md` | `sections/09-the-dawn-of-truth-part002-continuation.md` | 76–80 | continuation of frozen E9 / chapter7; **no repeated displayed chapter heading** |
| **E11** | `10-karagam-vidum-thiruvizha.md` | `sections/10-karagam-vidum-thiruvizha.md` | 81–89 | chapter8; source-facing romanized file handle; semantic English title deferred to source-check |
| **E12** | `11-maniyangurichchi-kurinji-maangal.md` | `sections/11-maniyangurichchi-kurinji-maangal.md` | 90–98 | chapter9; source-facing romanized file handle; semantic English title deferred |
| **E13** | `12-archchanai-yaar-vayirukku.md` | `sections/12-archchanai-yaar-vayirukku.md` | 99–108 | chapter10; preserve title wordplay/question until direct translation check |
| **E14** | `13-aasaiyil-arukkaani-thangam.md` | `sections/13-aasaiyil-arukkaani-thangam.md` | 109–118 | chapter11; semantic English title deferred |
| **E15** | `14-poonaiyil-porkkolam.md` | `sections/14-poonaiyil-porkkolam.md` | 119–127 | chapter12; semantic English title deferred |
| **E16** | `15-vazhiyil-vandha-vibareetham.md` | `sections/15-vazhiyil-vandha-vibareetham.md` | 128–137 | chapter13; semantic English title deferred |
| **E17** | `16-raachchaandaar-malai-nokki.md` | `sections/16-raachchaandaar-malai-nokki.md` | 138–145 | chapter14; preserve ellipsis; Part002 terminal continuation |

The romanized filenames for E11–E17 are provenance handles, not final semantic title decisions. Working English display titles must be source-checked before each batch closes.

## Chapter-title locks

Controlling Tamil titles are exactly:

- chapter7 continuation — `உண்மையின் உதயம்`; frozen Part001 English handling **The Dawn of Truth** carries forward without modifying E9;
- chapter8 — `கரகம் விடும் திருவிழா`;
- chapter9 — `மணியங்குறிச்சி குறிஞ்சி மான்கள்`;
- chapter10 — `அர்ச்சனை- யார் வயிறுக்கு?`;
- chapter11 — `ஆசையில் அருக்காணித் தங்கம்`;
- chapter12 — `பூனையில் போர்க்கோலம்`;
- chapter13 — `வழியில் வந்த விபரீதம்`;
- chapter14 — `ராச்சாண்டார் மலைநோக்கி...`.

No semantic English title is treated as final merely because it appears plausible during planning.

## Cross-Part chapter7 lock — E9 → E10

- frozen Part001 E9 — scans70–75 — remains unchanged;
- Part002 E10 — scans76–80 — is the same chapter7 continuation;
- 75→76 is **GENUINE CONTINUATION / AUDITED / PASS**;
- E10 may use frozen E9 only for already-established English name/term continuity and immediate sentence-level continuity;
- E10 must not rewrite or append to `sections/08-the-dawn-of-truth.md`;
- E10 creates a separate Part002 English file;
- E10 body must not invent a second displayed chapter number/title.

## Names, titles, kinship and glossary carry-forward

`GLOSSARY.md` is frozen Part001 evidence and must not be edited for Part002.

`PART_002_GLOSSARY.md` is the active Part002 glossary.

Rules:

- carry forward already-reconciled Part001 English forms when the same Tamil form recurs;
- preserve deliberate Part001 distinctions rather than flattening them;
- a Part002-only name/term receives a source-facing working form at its first source-check, based only on verified Part002 Tamil;
- no external spelling, map, gazetteer, encyclopedia or published translation overrides the project source;
- no Part002 English decision may silently normalize canonical or assembled Tamil.

## Quotations, songs, verse and source claims

- translate only from verified Part002 assembled Tamil;
- preserve meaningful line/block structure;
- do not import published/remembered English versions;
- preserve speaker/narrator framing around historical, social, religious and political claims;
- do not convert narrative/dialogue claims into project-authenticated factual assertions.

## Source-check standard

For every batch E10–E17:

1. compare the draft against the exact verified assembled Tamil file and, where needed, canonical page source-transcription blocks;
2. account for every literary paragraph/dialogue/display block;
3. retain internal physical source-boundary comments;
4. preserve source order and speaker/agency structure;
5. record omissions, duplicates, unsupported English insertions and unresolved holds explicitly;
6. require canonical Tamil edits caused by English = **0**;
7. require assembled Tamil edits caused by English = **0**;
8. require frozen Part001 English edits caused by Part002 = **0**;
9. require Part003 leakage = **0**;
10. preserve outgoing **145→146 PENDING Part003 direct witness**;
11. create `E##_SOURCE_CHECK.md` only when the complete E-batch closes **SOURCE-CHECKED / COMPLETE**.

## Batch discipline

E10 must close **draft + source-check** before E11 is considered closed.  
E11 must close before E12.  
E12 must close before E13.  
E13 must close before E14.  
E14 must close before E15.  
E15 must close before E16.  
E16 must close before E17.

A user-directed physical-page iteration may cross an E-batch boundary, but durable source-check closure remains batch-specific.

## Lifecycle after E17

After E10–E17 all close **SOURCE-CHECKED / COMPLETE**:

1. Part002 whole-Part glossary reconciliation;
2. English editorial review;
3. whole-Part bilingual review against verified Part002 Tamil;
4. release/readiness;
5. release-ready synchronization;
6. no-post-release textual-drift verification;
7. Part002 final closure / freeze.

Part003 canonical work remains blocked until Part002 final closure and direct Part003 intake/boundary witness.

## Planning gate result

**PART002 ENGLISH TRANSLATION PLANNING/SETUP — COMPLETE / PASS**

- reserved batches — **E10–E17 / 8**
- planned maintained English files — **8**
- complete planned source coverage — **scans76–145 / 70 scans**
- missing planned source coverage — **0**
- duplicate planned source coverage — **0**
- batch-number collisions — **0**
- English section-order collisions — **0**
- translated Part002 files — **0/8**
- source-checked Part002 files — **0/8**
- unresolved planning holds — **0**
- English literary prose drafted in planning gate — **0**
- canonical Tamil edits caused by planning — **0**
- assembled Tamil edits caused by planning — **0**
- frozen Part001 English edits caused by planning — **0**
- Part003 leakage — **0**
- outgoing 145→146 — **PENDING Part003 direct witness**

## Exact next activity

Process **E10 — Part002 chapter7 continuation — scans76–80**: draft the maintained English file and complete its direct source-check.

Do not begin E11 until E10 closes **SOURCE-CHECKED / COMPLETE**, unless the user explicitly directs a cross-batch physical-page iteration.
