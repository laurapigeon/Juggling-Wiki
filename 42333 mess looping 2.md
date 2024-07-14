---
props: 3
beats: 10
siteswap: "42333"
hands: (-30)(0).(-10)(10).(0)(0,-20)(-30).(-30,10)(30).(30)(-10).
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
