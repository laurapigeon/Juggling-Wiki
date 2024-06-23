---
props: 5
beats: 6
siteswap: "5"
hands: (-30)(-10).(-30)(-10).(30)(10).
siteswap pair:
  - "[[5b cascade]]"
  - "[[5b reverse cascade]]"
tags:
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
