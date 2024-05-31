---
aliases: 
props: 6
beats: 1
siteswap: (6,6)
hands: (10)(30).
alt siteswaps: 
sync pair:
  - "[[6b fountain]]"
symm pair: 
prop pair:
  - "[[fountain sync]]"
beat pair: 
reverse pair: 
tags:
  - sync
  - symm
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
