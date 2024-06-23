---
props: 3
beats: 6
siteswap: (6x,2x)(2x,6x)(0,2x)*
hands: (10)(20).(20)(30).(20)(20).(10)(20).(20)(30).(20)(20).
tags:
  - sync
  - symm
  - slam
aliases:
  - sprung 330
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
