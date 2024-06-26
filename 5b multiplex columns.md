---
props: 5
beats: 2
siteswap: ([44],[44])(4,0)
hands: (30)(0).(30)(30).(0)(30).(30)(30).
tags:
  - multiplex
  - asymm
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
