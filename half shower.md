---
aliases:
  - 3b half shower
props: 3
beats: 2
siteswap: "3"
hands: (10)(30).(30)(10).
alt siteswaps:
  - "522"
symm pair:
  - "[[reverse cascade]]"
siteswap pair:
  - "[[windmill]]"
  - "[[underarm tennis]]"
  - "[[tennis]]"
  - "[[reverse cascade]]"
  - "[[mills' mess]]"
  - "[[mills' mess windmill]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[half mills' mess]]"
  - "[[flo's mess]]"
  - "[[crossed arm cascade]]"
  - "[[crossed arm reverse cascade]]"
  - "[[cherry picker]]"
  - "[[charley]]"
  - "[[cascade]]"
  - "[[boston mess]]"
tags:
  - asymm
  - async
LoJ difficulty: 3
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
