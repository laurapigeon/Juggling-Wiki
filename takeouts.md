---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (-20)(0).(-30,60)(10,90).(0)(10,-10).(30,40)(-20).
alt siteswaps:
  - "423"
siteswap pair:
  - "[[423]]"
  - "[[burke's barrage]]"
  - "[[fake columns alternating]]"
  - "[[fake mills' mess]]"
  - "[[ping pong]]"
  - "[[reverse 423]]"
  - "[[the w]]"
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
