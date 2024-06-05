---
props: 3
beats: 4
siteswap: "3"
hands: (-30)(-10).(30)(-10).(30)(10).(-30)(10).
siteswap pair:
  - "[[boston mess]]"
  - "[[cascade]]"
  - "[[charley]]"
  - "[[half shower]]"
  - "[[mills' mess]]"
  - "[[reverse cascade]]"
  - "[[tennis]]"
hands pair:
  - "[[mills' mess]]"
tags: [asymm, async]
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
