---
aliases:
  - umbrella
props: 3
beats: 2
siteswap: (4x,4x)(4,0)
hands: (30,10)(0).(30,-10)(30).(0)(30).(30)(30).
prop pair:
  - "[[4b rainbow cross]]"
tags:
  - asymm
  - sync
LoJ difficulty: 3
siteswap pair:
  - "[[reverse crossunder]]"
  - "[[crossunder]]"
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
