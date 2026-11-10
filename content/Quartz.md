# Quartz config check
The following text is for debunging my forked of:
[quartz-community/obsidian-flavored-markdown](https://github.com/quartz-community/obsidian-flavored-markdown)
[Tim-Odermatt/quartz-obsidian-graphs](https://github.com/Tim-Odermatt/quartz-obsidian-graphs)
[DylanHojnoski/obsidian-graphs](https://github.com/DylanHojnoski/obsidian-graphs)
or just a list of cool features to remember.
## Add Highlighings from Obsidian [1.14.4](https://obsidian.md/changelog/2026-10-05-desktop-v1.14.4/)
Turning the ==highlight== into colored (🔴, 🟠, 🟡, 🟢, 🔵, 🟣) ==🔴hi== ==🟠g== ==🟡h== ==🟢li== ==🔵gh== ==🟣ts==.

==Default==
==🔴Red==
==🟠Orange==
==🟡Yellow==
==🟢Green==
==🔵Blue==
==🟣Purple==

---

# Custom [Minimal](https://github.com/kepano/obsidian-minimal) / [Things](https://github.com/colineckert/obsidian-things) theme features
- [ ] to-do
- [/] incomplete
- [x] done
- [-] canceled
- [>] forwarded
- [<] scheduling
- [?] question
- [!] important
- [*] star
- ["] quote
- [l] location
- [b] bookmark
- [i] information
- [S] savings
- [I] idea
- [p] pros
- [c] cons
- [f] fire
- [k] key
- [w] win
- [u] up
- [d] down

---


```graph
bounds: [-10, 10, 10, -10]
keepAspectRatio: true
axis: false
size: [600, 600]
elements: [
  # Triangle vertices
  {type: point, def: [-2, -4], att: {name: "A", size: 3}},
  {type: point, def: [4, 0], att: {name: "B", size: 3}},
  {type: point, def: [-4, 4], att: {name: "C", size: 3}},

  # Triangle sides
  {type: segment, def: [e0, e1], att: {name: "AB"}},
  {type: segment, def: [e1, e2], att: {name: "BC"}},
  {type: segment, def: [e2, e0], att: {name: "CA"}},

  # Altitudes
  {type: perpendicular, def: [e3, e2], att: {dash: 2, strokeWidth: 1, strokeColor: "#8000c0"}},
  {type: perpendicular, def: [e4, e0], att: {dash: 2, strokeWidth: 1, strokeColor: "#8000c0"}},
  {type: perpendicular, def: [e5, e1], att: {dash: 2, strokeWidth: 1, strokeColor: "#8000c0"}},

  # Orthocenter H
  {type: intersection, def: [e6, e8, 0], att: {name: "H", size: 3, strokeColor: "#8000c0", fillColor: "#8000c0"}},

  # Midpoints
  {type: midpoint, def: [e0, e1], att: {name: "Mab", size: 2, strokeColor: "#0080c0", fillColor: "#0080c0"}},
  {type: midpoint, def: [e1, e2], att: {name: "Mbc", size: 2, strokeColor: "#0080c0", fillColor: "#0080c0"}},
  {type: midpoint, def: [e2, e0], att: {name: "Mca", size: 2, strokeColor: "#0080c0", fillColor: "#0080c0"}},

  # Medians
  {type: segment, def: [e11, e0], att: {dash: 1, strokeColor: "#0080c0"}},
  {type: segment, def: [e12, e1], att: {dash: 1, strokeWidth: 1, strokeColor: "#0080c0"}},
  {type: segment, def: [e10, e2], att: {dash: 1, strokeWidth: 1, strokeColor: "#0080c0"}},
  # Centroid S
  {type: intersection, def: [e13, e15, 0], att: {name: "S", size: 3, strokeColor: "#0080c0", fillColor: "#0080c0"}},
  # Circumcircle
  {type: circumcircle, def: [e0, e1, e2], att: {strokeColor: "#ffaa00", strokeWidth: 1, dash: 0}},
  # Euler line
  {type: line, def: [e9, e16], att: {strokeWidth: 3, strokeColor: "#33aa66"}},
  # Circumcenter U
  {type: circumcenter, def: [e0, e1, e2], att: {name: "U", size: 3, strokeColor: "#ffaa00", fillColor: "#ffaa00"}}
]
```
