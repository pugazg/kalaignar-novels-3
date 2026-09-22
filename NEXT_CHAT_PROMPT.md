# NEXT CHAT PROMPT — பொன்னர் சங்கர் / Part001 final metadata-status synchronization

Continue directly in `pugazg/kalaignar-novels-3`, branch `main`, active work `works/ponnar-sankar/`. **LIVE MAIN IS AUTHORITATIVE.**

## Read first

1. `HANDOVER.md`
2. `works/ponnar-sankar/PART_001_AUDIT.md`
3. `works/ponnar-sankar/PART_001_PASS3_PROGRESS.md`
4. `works/ponnar-sankar/PART_001_PASS2B_PROGRESS.md`
5. `works/ponnar-sankar/PART_001_PASS2A_PROGRESS.md`
6. `works/ponnar-sankar/PART_001_PASS1_PROGRESS.md`
7. `works/ponnar-sankar/SOURCE_INTAKE_PART_001.md`
8. `works/ponnar-sankar/SOURCE_SPLIT_MANIFEST.md`
9. `works/ponnar-sankar/indexes/page-map.md`
10. `works/ponnar-sankar/PONNAR_SANKAR_ARCHIVAL_GUIDELINES.md`

Refetch live `main` before editing and again after the activity.

## Durable Part001 state

- source intake — **COMPLETE**
- canonical page records — **75/75**
- Pass 1 — **COMPLETE / 75/75**
- Pass 2A — **COMPLETE / 75/75 REVIEWED / PASS**
- Pass2A historical corrections — **31**
- **P2A-001 is superseded by P2B-001**
- Pass 2B — **COMPLETE / 75/75 REVIEWED / PASS**
- Pass2B corrections — **8**
- Pass2B unresolved textual questions — **0**
- Pass 3 — **COMPLETE / 75/75 REVIEWED / PASS**
- Pass3 structural corrections — **0**
- Pass3 unresolved visual / structural questions — **0**
- whole-Part audit — **PASS / COMPLETE — REVALIDATED AFTER CHAPTER-TITLE CORRECTION**
- audit blockers — **0**
- durable audit — `works/ponnar-sankar/PART_001_AUDIT.md`
- scan16 — **image-preserved map page** at `works/ponnar-sankar/assets/scan-0016-map.png`
- page records currently remain `status: "needs-review"` / `visual_fidelity: "needs-review"`
- assembled Tamil — **NOT STARTED**
- English — **BLOCKED pending Tamil closure**
- outgoing boundary **75→76 — PENDING Part002 direct witness**; this is not a Part001 audit blocker

## Chapter-title correction after audit

A source-backed title defect was found after the initial audit and has been corrected/revalidated.

Direct source opener verification:
- chapter1 / scan18 — `மண விழாவில் மச்சான்` — repository already matched source;
- chapter2 / scan26 — `விருந்தினர் விடுதியும் வேங்கைத் தோட்டியும்` — repository already matched source;
- chapter3 / scan34 — corrected from `மச்சசாமியும் மருமகியும்` to source-visible **`மச்சக்காரியும் மருமகளும்`**;
- chapter4 / scan43 — `இனிய சூழலும் புதிய கோலமும்` — repository already matched source.

Chapter3 canonical records scans34–42 were retitled, canonical filenames were renamed to `*-machchakkaariyum-marumagalum.md`, all maintained controls/page-map references were synchronized, and the affected audit scope was re-run **PASS**. The body dialogue `“எங்கே அந்த மச்சசாமி?”` remains unchanged because it is source body text, not the chapter title.

## Audit result

The whole-Part audit, including the post-audit chapter-title correction revalidation, is PASS / COMPLETE:

- continuous canonical coverage **1–75**
- canonical files **75**
- missing canonical records **0**
- duplicate canonical records **0**
- exactly one Pass1 / Pass2A / Pass2B / Pass3 evidence block per canonical page
- printed-page mapping reconciled with the maintained page map
- structural / chapter boundaries reconciled
- scan16 maintained image asset relationship confirmed
- unresolved in-scope blockers **0**
- no canonical Tamil changes made during audit

Three documentation-only inconsistencies were corrected during audit; no canonical page files were changed.

## Exact next activity — final metadata/status synchronization

Perform the post-audit promotion gate.

For all **75 canonical page records**:

1. change frontmatter `status: "needs-review"` → `status: "verified"`;
2. change frontmatter `visual_fidelity: "needs-review"` → `visual_fidelity: "verified"`;
3. make **no other canonical Tamil or structural edits**;
4. preserve all Pass evidence and page boundaries unchanged;
5. preserve scan16 as the image-backed map record.

After promotion:

6. verify **75/75** records now have `status: "verified"`;
7. verify **75/75** records now have `visual_fidelity: "verified"`;
8. verify there are **0** remaining `needs-review` values in Part001 canonical page frontmatter;
9. compare against the pre-promotion state and confirm no canonical text/body changes beyond the two frontmatter fields;
10. synchronize README, HANDOVER, source intake, split manifest, Pass progress files, audit record, page map, guidelines and `NEXT_CHAT_PROMPT.md`;
11. if all checks pass, mark **Tamil archival-ready — PASS / COMPLETE**.

Do **not** begin assembled Tamil construction in the same activity unless explicitly requested.

## Mandatory archive rules

- **LIVE MAIN IS AUTHORITATIVE.**
- metadata promotion is authorized because the whole-Part audit has passed
- change only the two status fields in canonical page records
- do not alter source transcription, punctuation, historical forms, headings, notes or Pass evidence
- no OCR-based Tamil verification
- scan16 remains image-preserved
- outgoing **75→76** remains pending until Part002 is supplied
- do not begin Part002 canonical transcription
- assembled Tamil starts only after Tamil archival-ready closes
