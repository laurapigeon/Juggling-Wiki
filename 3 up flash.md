---
props: 3
beats: 10
siteswap: "55500"
hands: (10)(30).(10)(30).(10)(30).(20)(20).(20)(20).
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
