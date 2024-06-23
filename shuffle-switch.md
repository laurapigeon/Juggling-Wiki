---
props: 3
beats: 3
siteswap: (4,4)(6,0)(2x,2x)
hands: (30)(0).(30)(30).(0)(30).(30)(30).(20,10)(20).(20)(20,10).
tags:
  - asymm
  - slam
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
