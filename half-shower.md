---
aliases:
  - 3b half shower
props: 3
beats: 2
siteswap: "3"
hands: (10)(30).(30)(10).
alt siteswaps:
  - "522"
sync pair: 
symm pair:
  - "[[reverse cascade|reverse cascade]]"
prop pair: 
beat pair: 
reverse pair: 
tags:
  - async
  - asymm
LoJ difficulty: 3
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
