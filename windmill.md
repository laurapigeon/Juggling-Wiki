---
props: 3
beats: 2
siteswap: "3"
hands: (30)(-10).(-30)(10).
siteswap pair:
  - "[[boston mess]]"
  - "[[cascade]]"
  - "[[charley]]"
  - "[[cherry picker]]"
  - "[[crossed arm cascade]]"
  - "[[crossed arm reverse cascade]]"
  - "[[flo's mess]]"
  - "[[half mess]]"
  - "[[half shower]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[mills' mess windmill]]"
  - "[[mills' mess]]"
  - "[[reverse cascade]]"
  - "[[tennis]]"
  - "[[underarm tennis]]"
tags:
  - asymm
  - async
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
