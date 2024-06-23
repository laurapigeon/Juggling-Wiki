---
props: 3
beats: 6
siteswap: (6x,2x)*
hands: (10)(30).(20)(20).
tags:
  - sync
  - symm
  - slam
aliases:
  - sprung 3
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
