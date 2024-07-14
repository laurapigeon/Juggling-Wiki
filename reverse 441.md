---
aliases:
  - 441 outside
props: 3
beats: 4
siteswap: "441"
hands: (30)(10).(10)(20).(20)(30).
reverse pair:
  - "[[441]]"
siteswap pair:
  - "[[441 mess]]"
  - "[[441]]"
tags:
  - async
  - slam
  - symm
LoJ difficulty: 4
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
