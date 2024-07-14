---
props: 3
beats: 4
siteswap: (4,2)(4x,2)*
hands: (30)(10).(20)(20).(30)(20).(20)(10).
alt siteswaps:
  - "423"
reverse pair:
  - "[[423]]"
siteswap pair:
  - "[[423]]"
  - "[[burke's barrage]]"
  - "[[fake columns alternating]]"
  - "[[fake mess]]"
  - "[[ping pong]]"
  - "[[takeouts]]"
  - "[[the w]]"
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
