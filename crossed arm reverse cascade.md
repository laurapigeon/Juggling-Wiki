---
props: 3
beats: 2
siteswap: "3"
hands: (-30)(-10).
siteswap pair:
  - "[[windmill]]"
  - "[[underarm tennis]]"
  - "[[tennis]]"
  - "[[reverse cascade]]"
  - "[[mills' mess]]"
  - "[[mills' mess windmill]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[half shower]]"
  - "[[half mills' mess]]"
  - "[[flo's mess]]"
  - "[[crossed arm cascade]]"
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
