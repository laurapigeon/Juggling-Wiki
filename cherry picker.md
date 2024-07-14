---
props: 3
beats: 6
siteswap: "3"
hands: (0,60)(30,60).(30)(0).(30,60)(-30,60).(0)(-30).(-30,60)(0,60).(-30)(30).
siteswap pair:
  - "[[windmill]]"
  - "[[underarm tennis]]"
  - "[[tennis]]"
  - "[[reverse cascade]]"
  - "[[mills' mess]]"
  - "[[mills' mess windmill]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[half shower]]"
  - "[[half mess]]"
  - "[[flo's mess]]"
  - "[[crossed arm cascade]]"
  - "[[crossed arm reverse cascade]]"
  - "[[charley]]"
  - "[[cascade]]"
  - "[[boston mess]]"
tags:
  - asymm
  - async
  - claw
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
