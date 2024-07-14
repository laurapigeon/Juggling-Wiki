---
props: 3
beats: 6
siteswap: "441"
hands: (-30)(10).(-30)(-10).(20)(10).
siteswap pair:
  - "[[reverse 441]]"
  - "[[441]]"
tags:
  - async
  - pass
  - symm
LoJ difficulty: 6
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
