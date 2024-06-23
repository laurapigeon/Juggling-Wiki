---
aliases:
  - boston shuffle box
props: 3
beats: 2
siteswap: (4x,2x)(2,4x)*
hands: (10)(20).(20)(30).(20)(30).(10)(20).
siteswap pair:
  - "[[boston shuffle orbit]]"
  - "[[boston shuffle]]"
  - "[[burke's slams]]"
  - "[[takeouts slams]]"
tags:
  - slam
  - symm
  - sync
sync pair:
  - "[[52512]]"
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
