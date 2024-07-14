---
props: 4
beats: 6
siteswap: "[34]23"
hands: (-30)(10).(-10,60)(30,60)(40,30)(20).(10)(-10).
tags:
  - async
  - multiplex
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
