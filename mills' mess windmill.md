---
props: 3
beats: 10
siteswap: "3"
hands: (-30)(-10).(30)(-10).(-30)(10).(30)(-10).(-30)(10).
siteswap pair:
  - "[[windmill]]"
  - "[[underarm tennis]]"
  - "[[tennis]]"
  - "[[reverse cascade]]"
  - "[[mills' mess]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[half shower]]"
  - "[[half mess]]"
  - "[[flo's mess]]"
  - "[[crossed arm cascade]]"
  - "[[crossed arm reverse cascade]]"
  - "[[cherry picker]]"
  - "[[charley]]"
  - "[[cascade]]"
  - "[[boston mess]]"
tags:
  - async
  - symm
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
