---
props: 5
beats: 2
siteswap: "5"
hands: (30)(10).
prop pair:
  - "[[reverse cascade]]"
reverse pair:
  - "[[5b cascade]]"
siteswap pair:
  - "[[5b mills' mess]]"
  - "[[5b cascade]]"
tags:
  - async
  - symm
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
