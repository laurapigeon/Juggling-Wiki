---
props: 4
beats: 2
siteswap: ([44x],2)(2,4x)
hands: (0)(30).(30)(30).(30)(30).(10)(30).
tags:
  - asymm
  - async
  - multiplex
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
