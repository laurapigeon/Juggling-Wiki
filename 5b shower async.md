---
props: 5
beats: 2
siteswap: "91"
hands: (20)(20).
sync pair:
  - "[[5b shower]]"
prop pair:
  - "[[2b shower async]]"
  - "[[4b shower async]]"
  - "[[shower async]]"
tags: [asymm, async, slam]
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
