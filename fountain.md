---
aliases:
  - 4b fountain
props: 4
beats: 2
siteswap: "4"
hands: (10)(30).
alt siteswaps: 
sync pair:
  - "[[fountain sync]]"
symm pair: 
prop pair:
  - "[[6b fountain]]"
beat pair: 
reverse pair: 
tags:
  - async
  - symm
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
