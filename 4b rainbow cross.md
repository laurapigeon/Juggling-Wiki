---
props: 4
beats: 2
siteswap: (4x,4x)(4,4)
hands: (30,10)(10).(30,-10)(10).(10)(30).(10)(30).
tags:
  - sync
  - asymm
prop pair:
  - "[[rainbow cross]]"
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
