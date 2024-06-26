---
props: 4
beats: 4
siteswap: ([4x4],2)(4x,2)*
hands: (-20)(0).(-30,60)(10,90).(0)(20,-10).(40,40)(-20,30).
tags:
  - carry
  - sync
  - symm
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
