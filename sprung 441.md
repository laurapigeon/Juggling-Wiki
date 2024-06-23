---
props: 4
beats: 6
siteswap: (8,2x)(2x,8)(2x,2x)*
hands: (10)(20).(20)(30).(20)(30).(10)(20).(20,10)(20,10).(20)(20).
tags:
  - symm
  - sync
  - slam
siteswap pair:
  - "[[inverted sprung 441]]"
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
