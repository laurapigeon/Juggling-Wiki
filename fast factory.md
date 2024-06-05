---
props: 3
beats: 2
siteswap: (2,4x)(2x,4)
hands: (30,60)(-30,60).(-30)(0).(-30,60)(30).(0)(30).
beat pair:
  - "[[factory]]"
tags: [asymm, carry, claw, drop, sync]
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
