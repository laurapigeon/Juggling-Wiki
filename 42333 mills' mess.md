---
props: 3
beats: 8
siteswap: "42333"
hands: (-30)(0).(-20)(-20).(0)(-30).(-30)(30).(30)(-10).
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
