---
props: 5
beats: 1
siteswap: (8x,2x)
hands: (20)(20).
sync pair:
  - "[[5b shower async]]"
prop pair:
  - "[[2b shower]]"
  - "[[4b shower]]"
  - "[[shower]]"
tags: [asymm, slam, sync]
LoJ difficulty: 9
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
