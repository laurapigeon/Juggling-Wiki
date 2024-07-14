---
props: 3
beats: 10
siteswap: "53133"
hands: (30)(10,30).(30)(10).(10,30)(10,30).(-30)(10).(-30,30)(30,30).
tags:
  - async
  - symm
  - slam
  - carry
  - claw
aliases:
  - frostbite tower
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
