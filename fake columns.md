---
props: 3
beats: 2
siteswap: (4,2)
hands: (30)(0).(30,-10)(30,50).(0)(30).(30,50)(30,-10).
symm pair:
  - "[[fake columns alternating]]"
siteswap pair:
  - "[[oy oy]]"
  - "[[yo yo]]"
hands pair:
  - "[[columns]]"
tags: [asymm, carry, sync]
LoJ difficulty: 2
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
