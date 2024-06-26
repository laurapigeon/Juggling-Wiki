---
props: 3
beats: 3
siteswap: (4x,2x)(2,4x)(2x,4)
hands: (20,-10)(30,60).(30)(20).(30,60)(-30,60).(-30)(0).(-30,60)(30).(0)(30).
tags:
  - sync
  - asymm
  - drop
  - carry
  - claw
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
