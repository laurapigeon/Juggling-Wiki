---
aliases: 
props: 6
beats: 2
siteswap: "6"
hands: (10)(30).
alt siteswaps: 
sync pair:
  - "[[6b fountain sync]]"
symm pair: 
prop pair:
  - "[[fountain]]"
beat pair: 
reverse pair: 
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
