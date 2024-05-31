---
aliases:
  - 3b shower
props: 3
beats: 1
siteswap: (4x,2x)
hands: (20)(20).
alt siteswaps:
  - "51"
sync pair: 
symm pair:
  - "[[box|box]]"
prop pair:
  - "[[2b shower]]"
  - "[[4b shower]]"
  - "[[5b shower]]"
beat pair: 
reverse pair: 
tags:
  - sync
  - async
  - asymm
  - slam
LoJ difficulty: 5
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
