---
props: 3
beats: 4
siteswap: (4,4)(4x,0)*
hands: (10)(30).(10)(10).(30)(10).(10)(10).
siteswap pair:
  - "[[columns alternating]]"
  - "[[infinity]]"
  - "[[reverse infinity]]"
tags: [symm, sync]
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
