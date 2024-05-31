---
aliases: 
props: 5
beats: 2
siteswap: "5"
hands: (10)(30).
alt siteswaps: 
sync pair: 
symm pair: 
prop pair:
  - "[[cascade]]"
beat pair: 
reverse pair:
  - "[[5b reverse cascade]]"
tags:
  - async
  - symm
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
