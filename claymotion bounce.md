---
props: 3
beats: 4
siteswap: (2,[2x2T])*
hands: (20,-10)(20,10)(20).(10)(30).
siteswap pair:
  - "[[underarm orbit]]"
  - "[[overarm orbit]]"
  - "[[claymotion takeouts]]"
tags:
  - multiplex
  - symm
  - sync
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
