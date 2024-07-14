---
props: 3
beats: 6
siteswap: (4,2)(4x,4x)(4x,0)*
hands: (-30)(30).(0,30)(0).(0)(30).(20,30)(20,60).(10)(30,20).(30,60)(30,20).
tags:
  - sync
  - symm
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
