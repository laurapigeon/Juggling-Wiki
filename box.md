---
aliases:
  - 3b box
props: 3
beats: 2
siteswap: (4,2x)*
hands: (20)(20).
sync pair:
  - "[[box async]]"
symm pair:
  - "[[shower]]"
prop pair:
  - "[[4b box]]"
beat pair:
  - "[[441 sync]]"
siteswap pair:
  - "[[n box]]"
  - "[[luke's shuffle]]"
  - "[[inverted box]]"
tags:
  - slam
  - symm
  - sync
LoJ difficulty: 6
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
