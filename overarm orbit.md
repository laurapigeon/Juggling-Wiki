---
props: 3
beats: 4
siteswap: (2,[2x2T])*
hands: (-20,10)(-10,-10)(20).(10)(20).
tags:
  - carry
  - multiplex
  - symm
  - sync
siteswap pair:
  - "[[underarm orbit]]"
  - "[[claymotion takeouts]]"
  - "[[claymotion bounce]]"
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
