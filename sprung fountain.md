---
props: 5
beats: 2
siteswap: (8,2x)*
hands: (10)(30).(20)(20).
tags:
  - sync
  - slam
  - symm
aliases:
  - sprung 4
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
