---
props: 5
beats: 1
siteswap: (6x,4x)
hands: (30)(10).(10)(30).
tags:
  - sync
  - asymm
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
