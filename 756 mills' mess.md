---
props: 6
beats: 6
siteswap: "756"
hands: (-30)(-10).(-30)(-10).(30)(-10).
tags:
  - symm
  - async
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
