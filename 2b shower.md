---
aliases: 
props: 2
beats: 1
siteswap: (2x,2x)
hands: (20)(20,10).(20,10)(20).
alt siteswaps:
  - "31"
sync pair: 
symm pair: 
prop pair:
  - "[[shower]]"
  - "[[4b shower]]"
  - "[[5b shower]]"
beat pair: 
reverse pair: 
tags:
  - sync
  - async
  - asymm
  - slam
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
