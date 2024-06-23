---
props: 4
beats: 30
siteswap: "53534"
hands: (-30)(-10).(-30)(-10).(30)(-10).(-30)(-10).(-30)(-10).(30)(10).(-30)(10).(-30)(-10).(30)(10).(-30)(10).(-30)(-10).(30)(10).(-30)(10).(-30)(-10).(30)(-10).
tags: [async, symm]
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
