---
aliases:
  - 3b mills mess
props: 3
beats: 6
siteswap: "3"
hands: (-30)(10).(30)(-10).(-30)(10).
alt siteswaps:
  - "522"
sync pair: 
symm pair: 
prop pair: 
beat pair: 
reverse pair: 
tags:
  - async
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
