---
props: 3
beats: 1
siteswap: "60"
hands: (10)(30).(20)(20).
alt siteswaps:
  - (6,0)
symm pair:
  - "[[6b fountain sync]]"
prop pair:
  - "[[two in one]]"
tags:
  - asymm
  - async
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
