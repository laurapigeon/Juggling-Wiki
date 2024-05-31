---
aliases: 
props: 3
beats: 6
siteswap: (2,4)(2,4x)(2x,4x)*
hands: (30)(30,60).(30)(0).(30,60)(-30,60).(-30)(30).(-30,60)(30).(0)(30).
alt siteswaps: 
sync pair: 
symm pair:
  - "[[factory]]"
prop pair: 
beat pair: 
reverse pair: 
tags:
  - sync
  - symm
  - carry
  - drop
  - claw
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
