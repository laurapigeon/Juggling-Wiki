---
aliases: [sync half box]
props: 3
beats: 2
siteswap: (4,2)(2x,4)*
hands: (10)(30).(20)(20).(20)(20).(10)(30).
sync pair:
  - "[[441]]"
beat pair:
  - "[[box]]"
tags: [slam, symm, sync]
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
