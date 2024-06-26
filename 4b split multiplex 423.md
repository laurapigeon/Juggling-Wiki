---
props: 4
beats: 4
siteswap: ([4x4],2)(4x,2)*
hands: (0)(30).(30)(30).(10)(30).(30)(30).
tags:
  - multiplex
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
