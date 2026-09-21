# Canonical Page Record Template — பொன்னர் சங்கர்

Use one canonical Markdown record per physical source scan.

```markdown
---
scan_page: <global physical scan>
part: <1-8>
part_page: <local physical page>
printed_page: <source-visible printed page or null>
work: "ponnar-sankar"
section: "<source-visible chapter/section label or structural description>"
page_type: "<source-supported classification>"
status: "needs-review"
visual_fidelity: "needs-review"
language: "ta"
source_filename: "<exact supplied PDF filename>"
transcription_method: "direct source-pixel transcription; PartXXX Pass 1 <batch>"
---

# <section title when source-supported>

## Source transcription

<source-visible Tamil only>

## Pass 1 notes

- <page structure / continuation / source-visible variants / printed-page note>
- status and visual fidelity remain needs-review

<!-- மூல மொத்த ஸ்கேன் பக்கம்: X; பகுதி: XXX; பகுதி உள்ளூர் பக்கம்: Y; அச்சுப் பக்கம்: Z; PASS 1 TEXT-COMPLETE / needs-review -->

## Formal PartXXX Pass 2A review

- direct word-by-word, punctuation, paragraph/dialogue, printed-pagination and physical page-boundary comparison completed against source pixels;
- source-text corrections: **<count>**;
- unresolved textual questions: **<count>**;
- Pass 2A result: **REVIEWED / PASS**;
- page remains needs-review pending later gates.

## Formal PartXXX Pass 2B review

- independent lexical / word-boundary / punctuation-sensitive and historical-glyph reread completed directly against source pixels;
- source-text / lexical / spacing / punctuation corrections: **<count>**;
- historical-glyph corrections: **<count>**;
- unresolved lexical / historical-glyph questions: **<count>**;
- Pass 2B result: **REVIEWED / PASS**;
- page remains needs-review pending later gates.

## Formal PartXXX Pass 3 review

- direct full-page visual / structural verification completed against the source image;
- structural classification confirmed: <classification>;
- heading hierarchy, paragraph/dialogue blocks, printed pagination, illustrations/furniture and physical page-boundary state checked;
- Pass-3 textual corrections: **<count>**;
- unresolved visual / structural questions: **<count>**;
- Pass 3 result: **REVIEWED / PASS**;
- page remains `status: "needs-review"` / `visual_fidelity: "needs-review"` pending Part audit and final metadata/status synchronization.
```

## Status rule

Do not set `verified` during Pass 1, Pass 2A, Pass 2B, Pass 3 or Part audit. Promote only after the whole-Part audit passes and the final metadata/status synchronization gate is explicitly performed.
