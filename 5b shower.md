---
aliases: 
props: 5
beats: 1
siteswap: (8x,2x)
hands: (20)(20).
alt siteswaps:
  - "91"
sync pair: 
symm pair:
  - "[[5b box]]"
prop pair:
  - "[[2b shower]]"
  - "[[shower]]"
  - "[[4b shower]]"
beat pair: 
reverse pair: 
tags:
  - sync
  - async
  - asymm
  - slam
LoJ difficulty: 9
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
