---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (30)(-10).(10)(-30).(-30)(20).(-30)(10).
siteswap pair:
  - "[[423]]"
  - "[[burke's barrage]]"
  - "[[fake columns alternating]]"
  - "[[ping pong]]"
  - "[[reverse 423]]"
  - "[[takeouts]]"
  - "[[the w]]"
hands pair:
  - "[[mills' mess]]"
tags: [carry, symm, sync]
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
