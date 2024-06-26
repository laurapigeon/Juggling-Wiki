---
props: 6
beats: 6
siteswap: ([4x4x],2)(2,4x)(4x,[22])*
hands: (10)(30).(20)(20).(20)(20).(10)(30).(10)(20).(20)(30).
tags:
  - asymm
  - async
  - multiplex
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
