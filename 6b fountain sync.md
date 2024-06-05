---
props: 6
beats: 1
siteswap: (6,6)
hands: (10)(30).
sync pair:
  - "[[6b fountain]]"
symm pair:
  - "[[three in one]]"
prop pair:
  - "[[fountain sync]]"
tags:
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
