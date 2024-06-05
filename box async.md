---
props: 3
beats: 6
siteswap: "612"
hands: (20)(20).
sync pair:
  - "[[box]]"
symm pair:
  - "[[shower async]]"
tags: [async, slam, symm]
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
