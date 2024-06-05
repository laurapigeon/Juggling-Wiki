---
props: 3
beats: 10
siteswap: "3"
hands: (-30)(-10).(30)(-10).(-20)(-30).(20)(-10).(-20)(10).
alt siteswaps:
  - "522"
siteswap pair:
  - "[[boston mess]]"
  - "[[cascade]]"
  - "[[half mills' mess]]"
  - "[[half shower]]"
  - "[[mills' mess]]"
  - "[[reverse cascade]]"
  - "[[tennis]]"
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
