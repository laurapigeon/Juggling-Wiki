---
props: 3
beats: 4
siteswap: (2x,4x)(4x,2)(2,4x)(2x,4x)
hands: (30)(0).(30)(-30,60).(0)(-30).(-30,60)(30,60).(30,60)(-30,60).(-30)(0).(-30,60)(30).(0)(30).
tags:
  - asymm
  - claw
  - carry
  - drop
  - sync
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
