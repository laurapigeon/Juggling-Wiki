---
aliases:
  - stacked multiplex cascade
props: 6
beats: 2
siteswap: "[33]"
hands: (10)(30).
alt siteswaps: 
sync pair: 
symm pair: 
prop pair: 
beat pair: 
reverse pair: 
tags:
  - async
  - asymm
  - multiplex
LoJ difficulty:
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
