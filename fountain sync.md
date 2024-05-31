---
aliases:
  - 4b sync fountain
props: 4
beats: 1
siteswap: (4,4)
hands: (10)(30).
alt siteswaps: 
sync pair:
  - "[[fountain]]"
symm pair: 
prop pair:
  - "[[6b fountain sync]]"
beat pair: 
reverse pair: 
tags:
  - sync
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
