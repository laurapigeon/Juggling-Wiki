---
props: 3
beats: 6
siteswap: "3"
hands: (0)(30).(30)(0).(30)(-30).(0)(-30).(-30)(0).(-30)(30).
alt siteswaps:
  - "522"
siteswap pair:
  - "[[cascade]]"
  - "[[charley]]"
  - "[[half mills' mess]]"
  - "[[half shower]]"
  - "[[mills' mess]]"
  - "[[reverse cascade]]"
  - "[[tennis]]"
tags: [asymm, async]
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
