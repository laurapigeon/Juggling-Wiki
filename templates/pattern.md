---
aliases: 
props: 
beats: 
siteswap: 
hands: 
alt siteswaps: 
sync pair: 
symm pair: 
prop pair: 
beat pair: 
reverse pair: 
tags: 
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
