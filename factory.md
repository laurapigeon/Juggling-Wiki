---
props: 3
beats: 3
siteswap: (2,4)(2,4x)(2x,4)
hands: (30)(30,60).(30)(0).(30,60)(-30,60).(-30)(30).(-30,60)(30).(0)(30).
symm pair:
  - "[[factory alternating]]"
beat pair:
  - "[[fast factory]]"
reverse pair:
  - "[[reverse factory]]"
tags:
  - asymm
  - carry
  - claw
  - drop
  - sync
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
