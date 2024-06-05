---
aliases: [3b shower]
props: 3
beats: 1
siteswap: (4x,2x)
hands: (20)(20).
sync pair:
  - "[[shower async]]"
symm pair:
  - "[[box]]"
prop pair:
  - "[[2b shower]]"
  - "[[4b shower]]"
  - "[[5b shower]]"
beat pair:
  - "[[shower stalled]]"
siteswap pair:
  - "[[low shuffle]]"
  - "[[shower cascade]]"
  - "[[shuffle]]"
tags: [asymm, slam, sync]
LoJ difficulty: 5
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
