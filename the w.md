---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (30)(0).(30)(30).(0)(30).(30)(30).
siteswap pair:
  - "[[423]]"
  - "[[burke's barrage]]"
  - "[[fake columns alternating]]"
  - "[[fake mess]]"
  - "[[ping pong]]"
  - "[[reverse 423]]"
  - "[[takeouts]]"
tags:
  - symm
  - sync
LoJ difficulty: 2
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
