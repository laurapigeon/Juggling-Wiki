---
props: 3
beats: 6
siteswap: (4,2x)(4x,2T)(4,2x)*
hands: (-30)(0).(20,60)(-30,60).(0)(-30).(-30,60)(10)(-30).(-30)(0).(-30)(30,60).
tags:
  - symm
  - sync
  - active2
  - drop
  - claw
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
