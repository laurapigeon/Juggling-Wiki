---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (-30)(10).(-30,40)(0,40).(30)(10,-20).(30)(10).
sync pair:
  - "[[423 mills' mess]]"
siteswap pair:
  - "[[weave]]"
  - "[[the w]]"
  - "[[takeouts]]"
  - "[[reverse 423]]"
  - "[[ping pong]]"
  - "[[fake mills' mess]]"
  - "[[fake columns alternating]]"
  - "[[423]]"
tags:
  - carry
  - symm
  - sync
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
