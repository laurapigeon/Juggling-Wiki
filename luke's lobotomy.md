---
props: 3
beats: 2
siteswap: (4x,2T)*
hands: (-30,40)(-10,40).(-10)(30,20)(-10,20).
tags:
  - sync
  - symm
  - active2
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
