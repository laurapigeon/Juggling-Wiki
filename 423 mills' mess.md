---
props: 3
beats: 6
siteswap: "423"
hands: (-30)(10).(-30)(10).(30)(10).
sync pair:
  - "[[burke's barrage]]"
hands pair:
  - "[[mills' mess]]"
tags: [async, carry, symm]
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
