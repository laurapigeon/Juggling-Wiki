---
aliases:
  - upsidedown box
props: 3
beats: 2
siteswap: (4,2x)*
hands: (10)(10,-10).(30,60)(30).
alt siteswaps:
  - "612"
symm pair:
  - "[[shuffle]]"
siteswap pair:
  - "[[box]]"
  - "[[inverted box]]"
  - "[[n box]]"
tags:
  - slam
  - symm
  - sync
LoJ difficulty: 7
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
