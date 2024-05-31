---
aliases:
  - split multiplex cascade
props: 5
beats: 2
siteswap: ([4x4],2)*
hands: (10)(30).
alt siteswaps:
  - "[32T]"
sync pair: 
symm pair: 
prop pair: 
beat pair: 
reverse pair: []
tags:
  - async
  - asymm
  - multiplex
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
