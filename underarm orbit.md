---
props: 3
beats: 4
siteswap: (2,[2x2T])*
hands: (-30,-20)(-20,30)(20).(10)(20).
siteswap pair:
  - "[[claymotion bounce]]"
  - "[[claymotion takeouts]]"
  - "[[overarm orbit]]"
tags: [carry, multiplex, symm, sync]
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
