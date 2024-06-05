---
props: 3
beats: 2
siteswap: (4,2)
hands: (30)(0,20).(0,60)(0).(0,20)(30).(0)(0,60).
siteswap pair:
  - "[[fake columns]]"
  - "[[yo yo]]"
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
