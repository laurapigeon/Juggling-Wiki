---
props: 4
beats: 2
siteswap: (8,2x)(2x,4)
hands: (10)(20).(20)(20).(20)(30).(20)(20).
tags:
  - asymm
  - sync
  - slam
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
