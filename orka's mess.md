---
props: 3
beats: 6
siteswap: (4,2)(4,4)(4x,0)*
hands: (-30)(10).(-30,50)(10,30).(30,30)(10).(-30)(-30).(30)(10).(20)(-10,30).
tags:
  - sync
  - symm
  - carry
beat pair:
  - "[[jeanne]]"
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
