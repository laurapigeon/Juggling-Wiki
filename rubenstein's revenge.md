---
props: 3
beats: 6
siteswap: "3"
hands: (-30)c(10,20)(0).(-30)(-10).(30)c(-10,30)(0,60)(10).
tags:
  - symm
  - async
  - carry
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
