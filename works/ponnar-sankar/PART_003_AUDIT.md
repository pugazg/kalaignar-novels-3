# Part 003 Whole-Part Audit — பொன்னர் சங்கர்

## Gate

**PART AUDIT — ACTIVATED / READY — NOT YET EXECUTED**

Audit scope:
- active Part — **Part003**
- global scans — **146–215**
- local pages — **1–70**
- controlling source — `TVA_BOK_0065560_பொன்னர்_சங்கர்_2017_part_003_pages_146-215.pdf`
- source SHA-256 — `3e1e742f27912797a3217e51e706caf75bbb4a74dd0b8c33116d6837df7c67ab`
- activation baseline live main — `1cf9b7be2e490011bcbdac9a02a0b3ba59480e6c`

This file activates the required whole-Part audit after Pass3. The activation checkpoint did **not** execute the audit checks, alter canonical Tamil, or promote page metadata.

## Closed prerequisite gates

- Pass1 — **COMPLETE / PASS — 70/70 TEXT-COMPLETE**
- Pass2A — **CLOSED / COMPLETE / PASS — 70/70 REVIEWED / 25 source-backed corrections / 0 unresolved**
- Pass2B — **CLOSED / COMPLETE / PASS — 70/70 REVIEWED / 11 source-backed corrections / 0 unresolved**
- Pass3 — **CLOSED / COMPLETE / PASS — 70/70 REVIEWED**
- Pass3 structural corrections — **0**
- Pass3 unresolved visual / structural questions — **0**
- Pass3 lexical reopenings — **0**
- all canonical Part003 records remain `status: "needs-review"` / `visual_fidelity: "needs-review"`

## Maintained audit methodology

Execute the whole-Part audit from **LIVE MAIN** using the Part001 / Part002 audit method. Do not promote metadata during the audit itself.

### 1. Canonical physical coverage

Verify:
- canonical Part003 page files found — **70 expected**
- expected scans — **146–215**
- actual `scan_page` values — continuous / unique
- actual `part_page` values — **1–70** continuous / unique
- `part: 3` on all records
- exact Part003 source filename on all records
- canonical paths unique
- page-map path reconciliation
- missing / duplicate records — none expected

### 2. Pass-evidence completeness

Verify every canonical Part003 record contains exactly once:
- Pass1 notes
- Formal Part003 Pass2A review
- Formal Part003 Pass2B review
- Formal Part003 Pass3 review

Verify closed-gate accounting:
- Pass2A corrections — **25**
- Pass2B corrections — **11**
- Pass3 structural corrections — **0**
- all unresolved textual / visual questions — **0**
- audit-entry metadata remains `needs-review` / `needs-review` on **70/70**

### 3. Printed-page mapping reconciliation

Reconcile canonical frontmatter with the maintained page map:

- scan146 — printed **129**
- scan147 — no ordinary running printed page
- scans148–154 — **131–137**
- scan155 — no ordinary running printed page
- scans156–163 — **139–146**
- scan164 — no ordinary running printed page
- scans165–172 — **148–155**
- scan173 — no ordinary running printed page
- scans174–180 — **157–163**
- scan181 — no ordinary running printed page
- scans182–190 — **165–173**
- scan191 — no ordinary running printed page
- scans192–199 — **175–182**
- scan200 — no ordinary running printed page
- scans201–207 — **184–190**
- scan208 — no ordinary running printed page
- scans209–215 — **192–198**

No missing running page number is to be inferred on decorative chapter-opening scans.

### 4. Structural / chapter-boundary reconciliation

Reconcile canonical records and Pass3 evidence for:

- scan146 — chapter14 `ராச்சாண்டார் மலைநோக்கி...` continuation and close
- scans147–154 — chapter15 `புறப்பட்டது போர்ப்படை`
- scans155–163 — chapter16 `போர்முனை எது?`
- scans164–172 — chapter17 `சங்கரன்மலையில் சந்திப்போம்?`
- scans173–180 — chapter18 `சுயநலமா? பொதுநலமா?`
- scans181–190 — chapter19 `உண்மையின் உறைவிடம்`
- scans191–199 — chapter20 `அப்பன் அருள்வாக்கு`
- scans200–207 — chapter21 `நேர்மையைப் பற்றி வீரமலை`
- scans208–215 — chapter22 `தியாகத்தின் எல்லை` continuing to the Part003 split edge

Verify chapter-opening/body/close classifications, intentional blank lower fields, displayed short-report lines, source-visible ornaments/illustrations, and physical page-end states recorded during Pass3.

### 5. Boundary audit state

Incoming:
- **145→146 — GENUINE CONTINUATION / AUDITED / PASS**
- durable witness — `PART_003_BOUNDARY_AUDIT_145_146.md`
- frozen Part002 reopening — **0 expected**

Outgoing:
- **215→216 — PENDING Part004 direct witness**
- scan215 remains the final supplied Part003 physical page
- scan216 wording inferred/imported — **0**
- chapter22 closure beyond scan215 must remain **NOT INFERRED**
- pending external witness is not an in-scope Part003 canonical defect

### 6. Unresolved-issue accounting

Verify:
- Pass1 source-reading holds — **0**
- Pass2A unresolved textual questions — **0**
- Pass2B unresolved textual questions — **0**
- Pass3 unresolved visual / structural questions — **0**
- audit coverage / duplicate / mapping / structure blockers — **0 expected**
- Parts001–002 reopening — **0**
- Part004 body leakage — **0**

### 7. Canonical immutability during audit

Require:
- canonical Tamil/body mutations during audit — **0**
- chapter-title mutations during audit — **0**
- source filename / scan identity mutations — **0**
- status promotions during audit — **0**
- visual-fidelity promotions during audit — **0**

Metadata promotion belongs only to the separate post-audit synchronization activity after a successful audit.

## Activation state

- audit checks executed in activation checkpoint — **NO**
- canonical Part003 body edits during activation checkpoint — **0**
- metadata promotions during activation checkpoint — **0**
- outgoing 215→216 — **PENDING Part004 direct witness**

## Exact next activity

Execute the **Part003 whole-Part audit** from LIVE MAIN using the checklist above.

Stop after producing the durable audit result. Do not perform final metadata/status promotion in the same audit activity.
