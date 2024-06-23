---
props: 3
beats: 2
siteswap: (2x,4x)(4,2)
hands: (30)(0).(30)(-30,60).(0)(-30).(-30,60)(30,60).
tags:
  - asymm
  - carry
  - claw
  - sync
beat pair:
  - "[[reverse factory]]"
reverse pair:
  - "[[fast factory]]"
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
