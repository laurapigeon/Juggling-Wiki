---
aliases: 
props: 3
beats: 3
siteswap: (2,4)(2,4x)(2x,4)
hands: (30)(30,60).(30)(0).(30,60)(-30,60).(-30)(30).(-30,60)(30).(0)(30).
alt siteswaps: 
sync pair: 
symm pair:
  - "[[factory alternating]]"
prop pair: 
beat pair:
  - "[[fast factory]]"
reverse pair:
  - "[[reverse factory]]"
tags:
  - sync
  - asymm
  - carry
  - drop
  - claw
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
