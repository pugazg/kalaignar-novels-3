# NEXT CHAT PROMPT — பொன்னர் சங்கர் / Part003 assembled Tamil construction + audit

Continue directly in `pugazg/kalaignar-novels-3`, branch `main`, active work `works/ponnar-sankar/`. **LIVE MAIN IS AUTHORITATIVE.**

## Frozen / closed state

Parts001–002 are **FINAL CLOSED / FROZEN**. Their canonical Tamil, assembled Tamil and maintained English must not be modified.

Part003 source:

`TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_003_pages_146-215.pdf`

- SHA-256 — `3e1e742f27912797a3217e51e706caf75bbb4a74dd0b8c33116d6837df7c67ab`
- global scans — **146–215**
- local pages — **1–70**
- incoming 145→146 — **GENUINE CONTINUATION / AUDITED / PASS**
- outgoing 215→216 — **PENDING Part004 direct witness**

Closed Part003 gates:

- Pass1 — **COMPLETE / PASS — 70/70**
- Pass2A — **CLOSED / COMPLETE / PASS — 70/70 — 25 corrections — 0 unresolved**
- Pass2B — **CLOSED / COMPLETE / PASS — 70/70 — 11 corrections — 0 unresolved**
- Pass3 — **CLOSED / COMPLETE / PASS — 70/70 — 0 structural corrections — 0 unresolved**
- whole-Part audit — **PASS / COMPLETE — 0 blockers**
- final metadata/status synchronization — **PASS / COMPLETE**
- canonical `status: verified` — **70/70**
- canonical `visual_fidelity: verified` — **70/70**
- Tamil archival-ready — **PASS / COMPLETE**
- durable audit — `works/ponnar-sankar/PART_003_AUDIT.md`
- durable archival-ready checkpoint — `works/ponnar-sankar/PART_003_TAMIL_ARCHIVAL_READY.md`

## Exact next activity

Construct and validate the **Part003 assembled Tamil reading layer**.

Use only verified canonical `pages/` records as Tamil authority.

### Required Part003 assembled files

Do **not** modify frozen Part001 or Part002 section files. In particular, keep `sections/16-raachchaandaar-malai-nokki.md` frozen at scans138–145.

Create new Part003 section files:

1. `sections/17-raachchaandaar-malai-nokki-part003-continuation.md` — scan146 — chapter14 continuation and close only; do not synthesize a new displayed chapter heading.
2. `sections/18-purappattathu-porppadai.md` — scans147–154 — chapter15.
3. `sections/19-pormunai-ethu.md` — scans155–163 — chapter16.
4. `sections/20-sangaranmalaiyil-santhippom.md` — scans164–172 — chapter17.
5. `sections/21-suyanalamaa-pothunalamaa.md` — scans173–180 — chapter18.
6. `sections/22-unmaiyin-uraividam.md` — scans181–190 — chapter19.
7. `sections/23-appan-arulvaakku.md` — scans191–199 — chapter20.
8. `sections/24-nermaiyai-patri-veeramalai.md` — scans200–207 — chapter21.
9. `sections/25-thiyaagaththin-ellai.md` — scans208–215 — chapter22 continuation to the Part003 split edge.

Coverage arithmetic:

- **1 + 8 + 9 + 9 + 8 + 10 + 9 + 8 + 8 = 70**

### Assembly rules

- literary body text comes only from each canonical page's `## Source transcription` block;
- for chapter-opening scans147/155/164/173/181/191/200/208, retain the source-visible chapter number/title display exactly once from that verified canonical opener;
- do not synthesize a new displayed heading for scan146 because chapter14 opened in frozen Part002;
- preserve canonical punctuation, paragraph/dialogue order, displayed verse/song/report blocks and historical forms;
- insert only non-rendering HTML comments for physical scan boundaries;
- exclude YAML/frontmatter, Pass notes, review/audit notes, running headers, printed-page furniture and archival copy marks from literary body;
- canonical pages must not be mutated by assembly;
- Parts001–002 section files must remain frozen;
- no Part004 wording may be inferred or imported.

### Validation / audit

After construction, independently reconstruct each Part003 section from live verified canonical pages and compare it to the committed assembled file.

Validate:

- assembled files — **9/9**
- exact Part003 canonical coverage — **70/70 scans146–215**
- missing coverage — **0**
- duplicate coverage — **0**
- Parts001–002 section mutation — **0**
- unsupported Tamil insertion — **0**
- Pass/review/audit/control-note leakage into literary text — **0**
- canonical Part003 page mutations caused by assembly — **0**
- Part004 body leakage — **0**
- opener-title derivation — **canonical only / PASS**
- outgoing 215→216 — **PENDING Part004 direct witness**

Create durable validation:

`works/ponnar-sankar/PART_003_ASSEMBLED_TAMIL_VALIDATION.md`

Synchronize `sections/README.md`, work controls, `HANDOVER.md`, root `README.md`, and `NEXT_CHAT_PROMPT.md`.

## Stop condition

Stop after **Part003 assembled Tamil — VERIFIED / PASS / CLOSED** and its assembled-Tamil audit/validation is complete.

Do **not** begin Part003 English translation in the same activity. The next activity after closure is **Part003 English translation planning/setup**.
