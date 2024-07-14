---
props: 3
beats: 8
siteswap: (4x,2)(2,4x)(4,4)(4x,0)*
hands: (-30)(10).(-30,50)(10,30).(30,50)(-10,30).(-30)(-10).(30,30)(10).(-30)(-30).(30)(10).(20)(-10,30).
tags:
  - sync
  - symm
  - carry
beat pair:
  - "[[orka's mess]]"
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
