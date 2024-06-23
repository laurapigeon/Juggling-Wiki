---
props: 3
beats: 4
siteswap: (4,4)(4x,0)*
hands: (20)(40).(20)(20).(10)(20).(20)(20).
reverse pair:
  - "[[reverse infinity]]"
siteswap pair:
  - "[[reverse infinity]]"
  - "[[columns overthrow]]"
  - "[[columns alternating]]"
tags:
  - symm
  - sync
LoJ difficulty: 3
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
