---
props: 2
beats: 1
siteswap: (2x,2x)
hands: (20,10)(20).(20)(20,10).
sync pair:
  - "[[2b shower async]]"
prop pair:
  - "[[4b shower]]"
  - "[[5b shower]]"
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
