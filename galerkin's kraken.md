---
props: 3
beats: 14
siteswap: "3"
hands: (-30)(0).(-30,40)(0,40).(-30)(0).(-30,40)(30,40).(0)(30).(30,40)(0,40).(30)(-30).
tags:
  - async
  - symm
  - claw
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
