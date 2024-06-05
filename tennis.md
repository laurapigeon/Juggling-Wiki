---
aliases:
  - juggler's tennis
props: 3
beats: 6
siteswap: "3"
hands: (10)(30).(0)(20).(30)(10).
alt siteswaps:
  - "522"
siteswap pair:
  - "[[boston mess]]"
  - "[[cascade]]"
  - "[[charley]]"
  - "[[half mills' mess]]"
  - "[[half shower]]"
  - "[[mills' mess]]"
  - "[[reverse cascade]]"
tags:
  - async
  - symm
LoJ difficulty: 2
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
