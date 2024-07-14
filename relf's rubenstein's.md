---
props: 3
beats: 14
siteswap: "5224233"
hands: (-30)(-10).(-40)(-20,30).(50)(20,20).(-40)(-10).(50)(30,60).(-30)(20).(-20,30)(10,30).
tags:
  - async
  - symm
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
