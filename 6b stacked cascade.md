---
aliases: [stacked multiplex cascade]
props: 6
beats: 2
siteswap: "[33]"
hands: (10)(30).
tags: [asymm, async, multiplex]
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
