---
props: 4
beats: 6
siteswap: "[24]24"
hands: (10)(30).(20)(20).(10)(30).
tags:
  - multiplex
  - async
  - symm
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
