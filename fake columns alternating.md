---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (30)(0).(30,-10)(30,50).(0)(30,-10).(30,50)(30).
symm pair:
  - "[[fake columns]]"
siteswap pair:
  - "[[weave]]"
  - "[[the w]]"
  - "[[takeouts]]"
  - "[[reverse 423]]"
  - "[[ping pong]]"
  - "[[fake mess]]"
  - "[[burke's barrage]]"
  - "[[423]]"
tags:
  - carry
  - symm
  - sync
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
