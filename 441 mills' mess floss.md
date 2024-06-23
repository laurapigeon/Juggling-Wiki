---
props: 3
beats: 14
siteswap: "4242441"
hands: (-30)(10).(-20)(20).(10)(-10).(20)(-20).(-30)(-10).(-30)(-20).(20)(10).
tags: [async, carry, pass, symm]
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
