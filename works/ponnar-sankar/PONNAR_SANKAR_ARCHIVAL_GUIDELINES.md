# பொன்னர் சங்கர் — Part-by-Part Archival Guidelines

## Controlling-source rule

The user-supplied split PDFs are the controlling source. Preserve source wording, punctuation, paragraphing, dialogue structure, historical glyph identity, printed pagination, illustrations, blank fields and page structure.

Rendered source pixels remain authoritative even when a PDF text layer exists.

## Multipart design

- complete source: **8 supplied split PDFs**
- each supplied split: **<=50 MB**
- split basis: **file size**, so local page counts may vary
- Parts: **Part001–Part008** in supplied order
- total physical scan extent: **to be established by intake**
- canonical `scan_page`: global physical order across the whole work; never resets
- every page record carries exact `part`, `part_page`, `source_filename` and source-visible `printed_page` when present

Never infer equal Part sizes and never infer a Part's global range before inspecting that split.

## Mandatory Part lock

> **Finish the entire maintained workflow for the active Part before beginning canonical transcription of the next Part.**

A later Part may be opened only as an adjacent boundary witness when needed for direct split-boundary classification.

## Tamil Part workflow

1. **Source intake**
   - exact filename
   - bytes
   - SHA-256
   - local physical PDF page count
   - global scan start/end
   - archive/source identity where source-visible
   - text-layer availability
   - rendered-page authority
2. **Pass 1 — complete physical capture/transcription**
   - canonical page records for every physical scan in the active Part
   - source-visible text only
   - preserve printed pagination and page type
   - record source-reading holds explicitly
3. **Pass 2A — direct textual verification**
   - word-by-word text
   - punctuation
   - paragraph/dialogue structure
   - printed pagination
   - physical page boundary
4. **Pass 2B — independent lexical / historical-glyph reread**
   - word boundaries
   - spacing
   - punctuation-sensitive readings
   - historical Tamil glyph identity
   - no silent modernization
5. **Pass 3 — meaningful full-page visual / structural verification**
   - headings
   - chapter boundaries
   - illustrations
   - captions
   - blank lower fields
   - spreads
   - recurring furniture
   - page-type classification
6. **Part audit**
   - complete continuous scan coverage
   - no duplicate/missing canonical records
   - Pass evidence complete
   - printed-page mapping reconciled
   - boundaries reconciled
   - unresolved issues explicitly counted
7. **Final metadata/status synchronization**
   - only after the Part audit passes
   - promote `status` and `visual_fidelity` to `verified`
   - do not alter canonical Tamil merely to perform status promotion
8. **Documentation synchronization**
   - handover
   - work README
   - source intake
   - page map
   - progress/audit records
9. **Tamil archival-ready checkpoint**
   - canonical Tamil verified
   - visual fidelity verified
   - unresolved Tamil/glyph/visual/structural/documentation blockers = 0

Final `verified` status is assigned only after the whole-Part Tamil verification chain closes.

## Pass separation

- Pass 2A cannot begin until Pass 1 covers the full active Part.
- Pass 2B cannot begin until Pass 2A closes.
- Pass 3 cannot begin until Pass 2B closes.
- Part audit cannot begin until Pass 3 closes.
- Metadata promotion cannot occur before Part audit passes.
- Assembled Tamil cannot begin before Tamil archival-ready closes.
- English cannot begin before assembled Tamil closes.
- Final closure must occur before the next Part's canonical transcription begins.

Pass 1 may be executed in smaller scan batches for practical handling; the Part gate remains open until all physical scans in the Part are text-complete.

## Boundary rule

For each split boundary `N→N+1`:

- inspect only the two adjacent controlling source scans;
- classify the boundary from direct evidence, for example **CLEAN**, **GENUINE CONTINUATION**, or another source-supported structural state;
- do not reconstruct missing wording across the boundary;
- do not import next-Part body text into the active Part;
- preserve a durable boundary-audit record when the outgoing witness becomes available.

The final Part has no outgoing next-Part witness.

## Canonical page-record schema

Each canonical page record follows the Paayum Puli model:

```yaml
---
scan_page: <global physical scan>
part: <1-8>
part_page: <local physical page>
printed_page: <source-visible printed page or null>
work: "ponnar-sankar"
section: "<source-visible chapter/section label or structural description>"
page_type: "<body|title|contents|illustration|spread|other source-supported type>"
status: "needs-review"
visual_fidelity: "needs-review"
language: "ta"
source_filename: "<exact supplied PDF filename>"
transcription_method: "direct source-pixel transcription; <Part/Pass1 batch>"
---
```

Use `needs-review` through Pass 1, Pass 2A, Pass 2B, Pass 3 and Part audit. Promote only during final metadata/status synchronization after the audit passes.

## Assembled Tamil workflow

After Tamil archival-ready:

1. construct maintained section/chapter files from verified canonical `pages/` only;
2. audit exact canonical coverage;
3. missing coverage = 0;
4. duplicate coverage = 0;
5. unsupported Tamil insertion = 0;
6. audit-note leakage = 0;
7. canonical page mutations caused by assembly = 0;
8. next-Part body leakage = 0;
9. close assembled Tamil as **VERIFIED / PASS / CLOSED**.

Canonical `pages/` remains the controlling Tamil authority.

## English workflow

After assembled Tamil closes:

1. English translation planning/setup;
2. reserve sequential E-batches without collision;
3. create Part translation plan, glossary and progress controls;
4. draft and source-check each English batch sequentially;
5. each batch must become **SOURCE-CHECKED / COMPLETE** before the next batch;
6. whole-Part glossary reconciliation;
7. English editorial review;
8. whole-Part bilingual review against verified Tamil;
9. release/readiness report;
10. release-ready synchronization;
11. verify no unauthorized canonical/assembled/English textual drift;
12. final closure — **PASS / CLOSED / FROZEN**.

English work must not modify verified canonical Tamil. Occurrence-sensitive names, titles and historical/source variants must not be silently homogenized.

## Source-file policy

Source PDFs are controlling evidence but remain outside Git. Repository records store source provenance, hashes, mappings, transcriptions, audits and derived maintained text.

## Current frontier

- Part001 — **SOURCE INTAKE COMPLETE / 75 canonical page records**
- Part001 Pass 1 — **COMPLETE**
- Part001 Pass 2A — **COMPLETE / 75/75 REVIEWED / PASS**
- Part001 Pass 2A corrections — **31 recorded historically; P2A-001 superseded by P2B-001**
- Part001 Pass 2A unresolved — **0**
- Part001 Pass 2B — **COMPLETE / 75/75 REVIEWED / PASS**
- Part001 Pass 2B corrections — **8**
- Part001 Pass 2B unresolved — **0**
- Part002 — **REGISTERED / COMPLETE — 70 pages / scans76–145**
- Part002 Pass1 — **COMPLETE / PASS — 70/70 TEXT-COMPLETE — scans76–145**
- Part002 Pass1 pending — **0/70**
- Part002 Pass2A — **CLOSED / COMPLETE / PASS — 70/70 REVIEWED — scans76–145**
- Part002 Pass2A source-text corrections — **47**
- Part002 Pass2A pending — **0/70**
- Part002 Pass2B — **IN PROGRESS — 50/70 REVIEWED / PASS — scans76–125**
- Part002 Pass2B source-text corrections — **15**
- Part002 Pass2B unresolved — **0**
- Part002 Pass2B pending — **20/70 — scans126–145**
- Part002 Pass2B cadence — **10 scans per iteration**
- Part002 Pass3 — **BLOCKED UNTIL PASS2B COMPLETE**
- Part003–Part008 — **pending intake / NOT REGISTERED**
- boundary 75→76 — **GENUINE CONTINUATION / AUDITED / PASS**
- outgoing Part002 boundary 145→146 — **PENDING Part003 direct witness**
- Part001 Pass 3 — **COMPLETE / 75/75 REVIEWED / PASS**
- Part001 Pass 3 structural corrections — **0**
- Part001 Pass 3 unresolved visual / structural questions — **0**
- Part001 Pass 3 cadence — **15 pages per iteration**
- Part001 Part audit — **PASS / COMPLETE**
- chapter-title source revalidation — **PASS / USER-CONFIRMED — chapters1–4 corrected; chapters5–7 confirmed unchanged**
- Part001 audit blockers — **0**
- durable audit — `PART_001_AUDIT.md`
- Part001 final metadata/status synchronization — **COMPLETE / 75/75 status verified / 75/75 visual verified**
- Part001 Tamil archival-ready — **PASS / COMPLETE**
- durable Tamil archival-ready checkpoint — `PART_001_TAMIL_ARCHIVAL_READY.md`
- Part001 assembled Tamil — **VERIFIED / PASS / CLOSED — 9/9 section files / exact canonical coverage 75/75**
- Part001 assembled-Tamil validation — `PART_001_ASSEMBLED_TAMIL_VALIDATION.md`
- Part001 English planning/setup — **COMPLETE / PASS**
- Part001 English batches — **E1–E9 reserved / 9**
- Part001 English planned coverage — **scans1–75 / 0 missing / 0 duplicate**
- Part001 complete translated/source-checked files — **9/9 / 9/9**
- E1–E9 — **SOURCE-CHECKED / COMPLETE**
- English physical processing coverage — **scans1–75 / 75 of 75**
- latest user-directed page iteration — **30 scans / scans46–75**
- whole-Part glossary reconciliation — **RECONCILED / PASS**
- glossary reconciliation section edits — **0**
- unresolved glossary holds — **0**
- English block-accounting mismatches — **0**
- English Part002 leakage — **0**
- active English controls — `translations/en/TRANSLATION_PLAN.md`, `translations/en/GLOSSARY.md`, `translations/en/PROGRESS.md`
- English editorial review — **PASS / CLOSED**
- whole-Part bilingual review — **PASS / CLOSED**
- release/readiness — **PASS / CLOSED**
- unresolved release blockers — **0**
- release-ready synchronization — **PASS / CLOSED**
- Part001 final closure — **PASS / CLOSED / FROZEN**
- chapter9 / scan90 — **`மணியங்குறிச்சி குறிஞ்சி மான்கள்`**
- chapter10 / scan99 — **`அர்ச்சனை- யார் வயிறுக்கு?`**
- chapter11 / scan109 — **`ஆசையில் அருக்காணித் தங்கம்`**
- chapter12 / scan119 — **`பூனையில் போர்க்கோலம்`**
- chapter13 / scan128 — **`வழியில் வந்த விபரீதம்`**
- chapter14 / scan138 — **`ராச்சாண்டார் மலைநோக்கி...`**
- exact next activity — **Part002 Pass2B Batch6 — scans126–135 / local pages51–60**
