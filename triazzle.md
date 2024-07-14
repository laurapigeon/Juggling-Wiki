---
props: 3
beats: 6
siteswap: (4,2)(4x,2)(4x,2x)*
hands: (30)(10).(20)(-30).(10)(30).(-30)(20).(30)(30).(20)(30).
tags:
  - sync
  - symm
  - pass
  - carry
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
