---
props: 5
beats: 2
siteswap: ([44],2x)*
hands: (20)(20).
tags:
  - slam
  - sync
  - symm
  - multiplex
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
