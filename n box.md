---
props: 3
beats: 2
siteswap: (4,2x)*
hands: (20)(30).(30,60)(20,-10).(30)(20).(20,-10)(30,60).(20)(30).(30,60)(20,-10).(30)(20).(20,-10)(30,60).
siteswap pair:
  - "[[luke's shuffle]]"
  - "[[inverted box]]"
  - "[[box]]"
tags:
  - asymm
  - slam
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
