---
props: 3
beats: 6
siteswap: "3"
hands: (10)(20).(10)(20).(-30)(20).
siteswap pair:
  - "[[boston mess]]"
  - "[[cascade]]"
  - "[[charley]]"
  - "[[cherry picker]]"
  - "[[crossed arm cascade]]"
  - "[[crossed arm reverse cascade]]"
  - "[[flo's mess]]"
  - "[[half mills' mess]]"
  - "[[half shower]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[mills' mess windmill]]"
  - "[[mills' mess]]"
  - "[[reverse cascade]]"
  - "[[tennis]]"
  - "[[windmill]]"
tags: [async, symm]
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
