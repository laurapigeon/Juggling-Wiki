---
props: 3
beats: 2
siteswap: (4,4)(4,0)
hands: (30)(0).(30)(30).(0)(30).(30)(30).
symm pair:
  - "[[columns alternating]]"
tags: [asymm, sync]
LoJ difficulty: 3
---

siteswap pair:
```dataview
LIST
WHERE siteswap = this.siteswap
WHERE file.name != this.file.name
```
```dataviewjs
dv.paragraph("```siteswap\npattern: " + dv.current().siteswap + "\nhands: " + dv.current().hands + "\ncolors: mixed\n```");
```
