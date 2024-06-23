---
props: 4
beats: 6
siteswap: (8,2x)(2x,8)(2x,2x)*
hands: (0)(40,60).(40,60)(20).(40,60)(20).(0)(40,60).(0)(0).(40,60)(40,60).
tags:
  - sync
  - symm
  - slam
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
