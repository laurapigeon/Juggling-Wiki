---
props: 3
beats: 2
siteswap: (4x,2)*
hands: (-20)(-10).(0,40)(30,60).
tags: [carry, symm, sync]
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
