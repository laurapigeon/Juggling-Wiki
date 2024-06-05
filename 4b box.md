---
props: 4
beats: 4
siteswap: (6,2x)(6,2x)*
hands: (10)(20).(20)(30).(10)(30).(20)(20).
alt siteswaps:
  - "81281"
symm pair:
  - "[[4b shower]]"
prop pair:
  - "[[box]]"
tags: [slam, symm, sync]
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
