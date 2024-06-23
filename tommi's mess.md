---
props: 3
beats: 5
siteswap: 3[43]032T
hands: (30)(10).(30)(10).(10)(-10).(-30)(-10).(-30)(10).
tags:
  - async
  - multiplex
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
