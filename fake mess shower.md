---
props: 3
beats: 10
siteswap: "44142"
hands: (-30)(-10).(30)(30).(0)(10).(30)(-10).(-30)(-30).
tags:
  - async
  - symm
  - slam
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
