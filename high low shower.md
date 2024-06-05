---
aliases: [hilo shower]
props: 3
beats: 2
siteswap: (6x,2x)(2x,2x)
hands: (20)(20).(20)(20).(20,10)(20).(20)(20,10).
hands pair:
  - "[[shower]]"
tags: [asymm, slam, sync]
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
