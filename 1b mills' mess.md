---
props: 1
beats: 6
siteswap: "1"
hands: (-10)(0).(0)(-10).(-10)(-10).
tags:
  - symm
  - async
  - pass
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
