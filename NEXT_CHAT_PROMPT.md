# NEXT CHAT PROMPT — பொன்னர் சங்கர் / Part002 assembled Tamil construction + audit

Continue directly in `pugazg/kalaignar-novels-3`, branch `main`, active work `works/ponnar-sankar/`. **LIVE MAIN IS AUTHORITATIVE.**

## Frozen / closed state

Part001 is **FINAL CLOSED / FROZEN**. Its canonical Tamil, assembled Tamil and maintained English must not be modified.

Part002 source:

`TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_002_pages_76-145.pdf`

- SHA-256 — `d6bfca1bb53a21c72e4eab0ca03db545c9cf7070cd3e2cf8eaca9d864596c6cd`
- global scans — **76–145**
- local pages — **1–70**
- incoming 75→76 — **GENUINE CONTINUATION / AUDITED / PASS**
- outgoing 145→146 — **PENDING Part003 direct witness**

Closed Part002 gates:

- Pass1 — **COMPLETE / PASS — 70/70**
- Pass2A — **CLOSED / COMPLETE / PASS — 70/70 — 47 corrections — 0 unresolved**
- Pass2B — **CLOSED / COMPLETE / PASS — 70/70 — 19 corrections — 0 unresolved**
- Pass3 — **COMPLETE / PASS — 70/70 — 0 structural corrections — 0 unresolved**
- whole-Part audit — **PASS / COMPLETE — 0 blockers**
- final metadata/status synchronization — **PASS / COMPLETE**
- canonical `status: verified` — **70/70**
- canonical `visual_fidelity: verified` — **70/70**
- Tamil archival-ready — **PASS / COMPLETE**
- durable audit — `works/ponnar-sankar/PART_002_AUDIT.md`
- durable archival-ready checkpoint — `works/ponnar-sankar/PART_002_TAMIL_ARCHIVAL_READY.md`

## Exact next activity

Construct and validate the **Part002 assembled Tamil reading layer**.

Use only verified canonical `pages/` records as Tamil authority.

### Required Part002 assembled files

Do **not** modify frozen Part001 section files. In particular, keep `sections/08-unmaiyin-uthayam.md` frozen at scans70–75.

Create new Part002 section files:

1. `sections/09-unmaiyin-uthayam-part002-continuation.md` — scans76–80 — chapter7 continuation only; do not synthesize a new displayed chapter heading.
2. `sections/10-karagam-vidum-thiruvizha.md` — scans81–89 — chapter8.
3. `sections/11-maniyangurichchi-kurinji-maangal.md` — scans90–98 — chapter9.
4. `sections/12-archchanai-yaar-vayirukku.md` — scans99–108 — chapter10.
5. `sections/13-aasaiyil-arukkaani-thangam.md` — scans109–118 — chapter11.
6. `sections/14-poonaiyil-porkkolam.md` — scans119–127 — chapter12.
7. `sections/15-vazhiyil-vandha-vibareetham.md` — scans128–137 — chapter13.
8. `sections/16-raachchaandaar-malai-nokki.md` — scans138–145 — chapter14 continuation to Part002 split edge.

### Assembly rules

- literary body text comes only from each canonical page's `## Source transcription` block;
- for chapter-opening scans81/90/99/109/119/128/138, retain the source-visible chapter number/title display once from that verified canonical opener;
- no new displayed heading is invented for scans76–80 because chapter7 opened in frozen Part001;
- preserve canonical punctuation, paragraph/dialogue order, displayed verse/song blocks and historical forms;
- insert only non-rendering HTML comments for physical scan boundaries;
- exclude YAML/frontmatter, Pass notes, review/audit notes, running headers, printed-page furniture and archival copy marks from literary body;
- canonical pages must not be mutated by assembly;
- no Part003 wording may be inferred or imported.

### Validation / audit

After construction, independently reconstruct each Part002 section from live verified canonical pages and compare it to the committed assembled file.

Validate:

- assembled files — **8/8**
- exact Part002 canonical coverage — **70/70 scans76–145**
- missing coverage — **0**
- duplicate coverage — **0**
- Part001 section mutation — **0**
- unsupported Tamil insertion — **0**
- Pass/review/audit/control-note leakage into literary text — **0**
- canonical Part002 page mutations caused by assembly — **0**
- Part003 body leakage — **0**
- opener-title derivation — **canonical only / PASS**
- outgoing 145→146 — **PENDING Part003 direct witness**

Create durable validation:

`works/ponnar-sankar/PART_002_ASSEMBLED_TAMIL_VALIDATION.md`

Synchronize `sections/README.md`, work controls, `HANDOVER.md`, root `README.md`, and `NEXT_CHAT_PROMPT.md`.

## Stop condition

Stop after **Part002 assembled Tamil — VERIFIED / PASS / CLOSED** and its assembled-Tamil audit/validation is complete.

Do **not** begin Part002 English translation in the same activity. The next activity after closure is **Part002 English translation planning/setup**.
