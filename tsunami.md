---
props: 4
beats: 5
siteswap: "72416"
hands: (-30)(10).(20)(20).(10)(20).(10)(10).(20)(10).
tags:
  - async
  - symm
  - slam
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
