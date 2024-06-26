---
props: 4
beats: 2
siteswap: (4x,4x)
hands: (10,-10)(30).(30,10)(10).(30,10)(10).(10,-10)(30).
tags:
  - sync
  - symm
aliases:
  - 4b arches
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
