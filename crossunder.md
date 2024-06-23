---
props: 3
beats: 2
siteswap: (4x,4x)(4,0)
hands: (-30)(0).(-30)(30).(0)(30).(30)(30).
reverse pair:
  - "[[reverse crossunder]]"
siteswap pair:
  - "[[reverse crossunder]]"
  - "[[rainbow cross]]"
tags:
  - asymm
  - sync
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
