---
props: 3
beats: 4
siteswap: (4,4)(4x,0)*
hands: (20)(10).(20)(20).(40)(20).(20)(20).
reverse pair:
  - "[[infinity]]"
siteswap pair:
  - "[[columns alternating]]"
  - "[[columns overthrow]]"
  - "[[infinity]]"
tags: [symm, sync]
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
