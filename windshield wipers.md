---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (-30)(0).(30,60)(-30,60).(0)(30,60).(-30,60)(-30).
tags:
  - carry
  - sync
  - symm
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
