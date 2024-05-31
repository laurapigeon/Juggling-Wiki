---
aliases:
  - inverted shower
props: 3
beats: 1
siteswap: (4x,2x)
hands: (10)(30,60).(30,60)(10).
alt siteswaps:
  - "51"
sync pair: 
symm pair:
  - "[[inverted box]]"
prop pair: 
beat pair: 
reverse pair: 
tags:
  - sync
  - async
  - asymm
  - slam
LoJ difficulty: 7
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
