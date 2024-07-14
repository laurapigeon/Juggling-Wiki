---
props: 3
beats: 6
siteswap: "52233"
hands: (-30)(10).(-40)(0,30).(40)(0,30).(-30)(-10).(30)(-10).
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
