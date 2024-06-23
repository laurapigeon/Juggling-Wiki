---
aliases: [4b sync fountain]
props: 4
beats: 1
siteswap: (4,4)
hands: (10)(30).
sync pair:
  - "[[fountain]]"
prop pair:
  - "[[6b fountain sync]]"
tags: [symm, sync]
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
