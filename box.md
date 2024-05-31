---
aliases:
  - 3b box
props: 3
beats: 2
siteswap: (4,2x)*
hands: (20)(20).
alt siteswaps:
  - "612"
sync pair: 
symm pair:
  - "[[shower|shower]]"
prop pair: 
beat pair:
  - "[[441 sync]]"
reverse pair: 
tags:
  - sync
  - async
  - symm
  - slam
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
