---
props: 3
beats: 4
siteswap: ([2x2],2)(2T,[22])*
hands: (-20,-10)(-20,-10).(-20)(-20).(-20,-10)(20)(-20).(-20)(-20,10).
tags:
  - multiplex
  - symm
  - sync
siteswap pair:
  - "[[sky's pop]]"
  - "[[sky's drip]]"
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
