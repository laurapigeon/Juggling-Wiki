---
props: 3
beats: 10
siteswap: "3"
hands: (-20)(0).(10)(0).(10)(0).(-20)(0).(30)(-10).
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
