---
props: 5
beats: 2
siteswap: "5"
hands: (10,-10)(30).(30,10)(10).
tags:
  - async
  - asymm
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
