---
aliases: 
props: 3
beats: 3
siteswap: (4x,2)(0,[4x4])(0,4x)*
hands: (30)(10).(10)(10).(10)(10).(30)(10).(10)(10).(30)(10).
alt siteswaps:
  - 3[34]032
sync pair: 
symm pair:
  - "[[ripley's windmill]]"
prop pair: 
beat pair: 
reverse pair: 
tags:
  - async
  - symm
  - multiplex
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
