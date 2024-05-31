---
aliases: 
props: 3
beats: 3
siteswap: (4x,2x)
hands: (20)(20).(20)(20).(20)(20).(20)(20).(20)(20).(20)(-30,-10).
alt siteswaps:
  - "51"
sync pair: 
symm pair: 
prop pair: 
beat pair: 
reverse pair: 
tags:
  - sync
  - async
  - asymm
  - slam
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
