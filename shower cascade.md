---
props: 3
beats: 3
siteswap: (4x,2x)
hands: (20)(20).(20)(20).(20)(20).(20)(20).(20)(20).(20)(-30,-10).
siteswap pair:
  - "[[low shuffle]]"
  - "[[shower]]"
  - "[[shuffle]]"
tags: [asymm, slam, sync]
LoJ difficulty: 4
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
