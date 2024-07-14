---
props: 3
beats: 2
siteswap: "3"
hands: (30,10)(-10,-10).(-30)c(10)(-20,10).
tags:
  - async
  - asymm
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
