---
props: 3
beats: 6
siteswap: "441333"
hands: (-30)(10).(-30)(-10).(10)(10).(-30)(10).(-30)(-10).(30)(-10).
tags:
  - asymm
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
