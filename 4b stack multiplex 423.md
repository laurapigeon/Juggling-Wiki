---
props: 4
beats: 4
siteswap: (4,2)([4x4x],2)*
hands: (10)(30).(20)(20).(10)(20).(20)(30).
tags:
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
