---
props: 3
beats: 4
siteswap: (4x,2x)(2,4x)*
hands: (20)(10,20).(30,60)(20,-10).(-30,60)(20).(-10)(0,90).
siteswap pair:
  - "[[boston box]]"
  - "[[boston shuffle orbit]]"
  - "[[boston shuffle]]"
  - "[[burke's slams]]"
tags: [carry, slam, symm, sync]
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
