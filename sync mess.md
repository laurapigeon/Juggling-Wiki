---
props: 3
beats: 4
siteswap: (4x,4x)(4x,0)*
hands: (-30)(10).(-30)(10).(30,30)(-10).(10)(-10,30).
tags:
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
