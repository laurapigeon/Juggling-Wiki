---
props: 3
beats: 10
siteswap: 42T42T3
hands: (30)c(-10)(0,-10).(-20)(0,-20)(10).(30)(-10).(-30)(-20,-20)(-30).(-30)(30).
tags:
  - async
  - symm
  - carry
  - active2
beat pair:
  - "[[234 mess]]"
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
