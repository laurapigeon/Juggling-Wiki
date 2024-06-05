---
props: 3
beats: 3
siteswap: (4x,2)(0,[44x])(0,4)
hands: (-30)(20).(10)(-10).(20)(20).(30)(-10).(30)(10).(30)(10).
alt siteswaps:
  - 3[34]0422
symm pair:
  - "[[ripley's rainbow]]"
tags: [asymm, async, multiplex]
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
