---
props: 4
beats: 4
siteswap: ([4x4],2x)(4,2)*
hands: (10)(20).(20)(30).(30)(20).(20)(10).
alt siteswaps:
  - "[43]14"
tags: [multiplex, slam, symm, sync]
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
