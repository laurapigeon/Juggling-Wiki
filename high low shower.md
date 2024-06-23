---
aliases:
  - hilo shower
props: 3
beats: 2
siteswap: "7131"
hands: (20)(20).
tags:
  - asymm
  - slam
  - async
sync pair:
  - "[[sprung 31]]"
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
