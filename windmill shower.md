---
props: 3
beats: 4
siteswap: "4413"
hands: (-30)(0).(30)(30).(0)(10).(30)(-10).
tags:
  - async
  - asymm
  - slam
symm pair:
  - "[[mills' mess shower]]"
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
