---
props: 3
beats: 4
siteswap: (4x,2x)(2,4x)*
hands: (20)(30).(30,60)(20,-10).(30)(20).(0)(30,60).
siteswap pair:
  - "[[takeouts slams]]"
  - "[[burke's slams]]"
  - "[[boston shuffle orbit]]"
  - "[[boston box]]"
tags:
  - slam
  - symm
  - sync
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
