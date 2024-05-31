---
aliases: 
props: 3
beats: 3
siteswap: (4x,2)(0,[4x4])(0,4)
hands: (-30)(20).(10)(-10).(20)(20).(30)(-10).(30)(10).(30)(10).
alt siteswaps:
  - 3[34]0422
sync pair: 
symm pair:
  - "[[ripley's rainbow]]"
prop pair: 
beat pair: 
reverse pair: 
tags:
  - async
  - asymm
  - multiplex
LoJ difficulty:
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
