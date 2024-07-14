---
props: 3
beats: 6
siteswap: "3"
hands: (-10)(30).(-10)(-30).(10)(-30).
tags:
  - async
  - symm
reverse pair:
  - "[[mills' mess]]"
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
