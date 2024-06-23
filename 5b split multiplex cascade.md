---
props: 5
beats: 2
siteswap: ([44x],2)*
hands: (0)(30).(30)(30).
alt siteswaps:
  - "[32T]"
tags:
  - asymm
  - async
  - multiplex
LoJ difficulty: 6
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
