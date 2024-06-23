---
props: 3
beats: 4
siteswap: ([2x2],2)(2T,[22])*
hands: (-10,40)(-10,40).(-10)(-10).(-10,40)(10)(-10).(-10)(-10,-20).
siteswap pair:
  - "[[sky's pop]]"
  - "[[sky's skip]]"
tags: [multiplex, symm, sync]
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
