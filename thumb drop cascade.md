---
props: 3
beats: 2
siteswap: "[12][21]"
hands: (0,10)(10).
siteswap pair:
  - "[[claymotion cascade]]"
tags: [async, multiplex, symm]
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
