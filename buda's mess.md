---
props: 3
beats: 14
siteswap: "5151234"
hands: (30)(30).(0)(10).(30,100)(3,120).(30,100)(0).(-30,30)(-30).(-30)(10).(-30)(-10).
tags:
  - async
  - symm
  - slam
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
