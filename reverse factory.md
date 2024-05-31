---
aliases: 
props: 3
beats: 3
siteswap: (2x,4x)(4,2)(4,2)
hands: (30)(0).(30)(-30,60).(30)(-30).(-30,60)(30,60).(0)(30).(30,60)(30).
alt siteswaps: 
sync pair: 
symm pair: 
prop pair: 
beat pair: 
reverse pair:
  - "[[factory]]"
tags:
  - sync
  - asymm
  - carry
  - drop
  - claw
LoJ difficulty: 4
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
