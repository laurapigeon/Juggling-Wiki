---
aliases:
  - 522 mills' mess
props: 3
beats: 6
siteswap: "522"
hands: (-30)(-10).(-10)(10).(10)(-10).
siteswap pair:
  - "[[3b high cascade]]"
tags:
  - async
  - carry
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
