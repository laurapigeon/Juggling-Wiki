---
props: 3
beats: 4
siteswap: (4,4)(4x,0)*
hands: (30)(0).(30)(30).(0)(30).(30)(30).
symm pair:
  - "[[columns]]"
siteswap pair:
  - "[[columns overthrow]]"
  - "[[infinity]]"
  - "[[reverse infinity]]"
tags: [symm, sync]
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
