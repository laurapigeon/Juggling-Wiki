---
aliases:
  - 4b wimpy
props: 4
beats: 1
siteswap: (4x,4x)
hands: (10,10)(30).(10,-10)(30).
prop pair:
  - "[[rainbow cross]]"
tags:
  - asymm
  - sync
siteswap pair:
  - "[[4b half shower]]"
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
