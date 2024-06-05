---
props: 3
beats: 1
siteswap: (4x,2x)
hands: (20)(30).(30,60)(10,-10).
symm pair:
  - "[[luke's shuffle]]"
siteswap pair:
  - "[[low shuffle]]"
  - "[[shower cascade]]"
  - "[[shower]]"
tags: [asymm, slam, sync]
LoJ difficulty: 7
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
