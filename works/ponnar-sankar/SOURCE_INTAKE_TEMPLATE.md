# Source Intake — பொன்னர் சங்கர் — Part XXX

Source: `<exact supplied filename>`

## Intake result

**PENDING**

- local PDF pages: **<count>**
- canonical overall scans: **<start–end>**
- complete-source extent: **pending until Part008 intake unless independently established**
- file size: **<bytes>**
- SHA-256: **<sha256>**
- source text layer: **<usable / unusable / absent / not relied upon>**
- controlling representation: **rendered source page images**
- source family / archive identifier: **<source-visible identifier or pending>**
- work: **பொன்னர் சங்கர்**
- author: **கலைஞர் மு. கருணாநிதி**
- Part XXX local page 1 = overall scan **<start>**
- Part XXX local page <N> = overall scan **<end>**
- repository `scan_page` continues the whole-work sequence and never restarts

## Boundary state

- incoming split boundary: **<NONE for Part001 / pending / classification>**
- outgoing split boundary: **<pending until PartXXX+1 adjacent witness is supplied and directly checked>**

No text is reconstructed across a split boundary. Boundary classification comes only from adjacent source scans.

## Canonical page provenance

Every page record from this Part must preserve:

```yaml
part: <integer>
part_page: <1-N>
source_filename: "<exact supplied filename>"
```

Canonical `scan_page` remains the global physical scan number.

## Intake gate checklist

- [ ] exact filename recorded
- [ ] bytes recorded
- [ ] SHA-256 recorded
- [ ] local physical page count verified
- [ ] global scan range assigned without gaps/overlap
- [ ] source identity recorded where available
- [ ] rendered-page authority recorded
- [ ] manifest row synchronized
- [ ] page-map placeholder range added if useful
- [ ] incoming boundary status recorded
- [ ] outgoing boundary left pending unless adjacent witness exists

## Exact next activity

After intake closes, begin **PartXXX Pass 1**. Do not begin Pass 2A until all physical pages in this Part are text-complete.
