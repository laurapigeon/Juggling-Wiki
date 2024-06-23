---
props: 4
beats: 2
siteswap: "53"
hands: (10)(30).
tags:
  - asymm
  - async
siteswap pair:
  - "[[53 mills' mess]]"
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
