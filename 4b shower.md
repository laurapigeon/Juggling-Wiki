---
aliases: 
props: 4
beats: 1
siteswap: (6x,2x)
hands: (20)(20).
alt siteswaps:
  - "71"
sync pair: 
symm pair:
  - "[[4b box]]"
prop pair:
  - "[[2b shower]]"
  - "[[shower]]"
  - "[[5b shower]]"
beat pair: 
reverse pair: 
tags:
  - sync
  - async
  - asymm
  - slam
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
