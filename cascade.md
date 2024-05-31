---
aliases:
  - 3b cascade
props: 3
beats: 2
siteswap: "3"
hands: (10)(30).
alt siteswaps:
  - "522"
sync pair: 
symm pair: 
prop pair:
  - "[[5b cascade]]"
beat pair: 
reverse pair: 
tags:
  - async
  - symm
LoJ difficulty: 2
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
