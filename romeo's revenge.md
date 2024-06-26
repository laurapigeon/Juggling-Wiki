---
props: 3
beats: 6
siteswap: "3"
hands: (-30)(10,20).(-30)(-10).(-30,20)c(-10,20)(-30,50)(-10,60)(0).
tags:
  - carry
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
