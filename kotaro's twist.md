---
props: 3
beats: 4
siteswap: (4,[2x2])(2x,2)
hands: (0)(30).(30)(0).(30)(0).(-30,60)(-30,60).(0)(30).(-30,60)(-30,60).(30)(0).(0)(30).
tags: [asymm, multiplex, slam, sync]
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
