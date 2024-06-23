---
props: 3
beats: 4
siteswap: (4,[22x])(2,2)*
hands: (20)(20).
tags: [multiplex, symm, sync]
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
