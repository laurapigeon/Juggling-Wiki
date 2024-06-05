---
props: 3
beats: 2
siteswap: (4x,2x)(2,4)
hands: (20)(20).(20)(30).(20)(20).(10)(30).
beat pair:
  - "[[shower]]"
tags: [asymm, slam, sync]
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
