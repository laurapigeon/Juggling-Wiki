---
aliases:
  - 525 mills' mess
props: 4
beats: 6
siteswap: "552"
hands: (30)(10).(-30)(-10).(-30)(10).
tags:
  - async
  - symm
siteswap pair:
  - "[[4b fake mess]]"
  - "[[552]]"
prop pair:
  - "[[burke's barrage]]"
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
