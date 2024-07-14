---
props: 3
beats: 10
siteswap: "44133"
hands: (-30)(0).(30)(30).(0)(10).(30)(-10).(-30)(10).
tags:
  - async
  - symm
  - slam
symm pair:
  - "[[windmill shower]]"
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
