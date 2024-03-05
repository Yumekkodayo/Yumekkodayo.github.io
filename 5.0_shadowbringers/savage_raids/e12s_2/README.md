---
layout: default
title: E12S P2
parent: 零式レイド
nav_order: "12_2"
grand_parent: 5.0 漆黒のヴィランズ
permalink: /5.0_shadowbringers/savage_raids/e12s_2/
---

# Eden's Promise: Eternity (Savage) - Part 2

[Thoughts Per Second (TPS) strat](https://youtu.be/eBdHx53XteI)

Note: There are some details that are added in the macro, in particular, a DPS priority order for Basic Relativity.

### Things to check on Party Finder

- **Shockwave Pulsars**: The MT usually Reprisals all the Relativities, while the OT usually reprisals Shockwave Pulsars.
- **Somber Dance**: The way EN and JP parties bait Somber Dance differs- EN parties will tend to bait next to the boss, while JP will bait on the other side of the arena. MT usually baits first.
- **Advanced Relativity**: The macro has D3 and D4 adjust in the event D1+D3 or D2+D4 have the same (non-Fire) debuffs. Some macros have D2 and D3 adjust instead.
  - Having D3 and D4 adjust means that each side is guaranteed to have one melee DPS, one ranged DPS so there's no confusion over Dark Fire spots.
  - Having D2 and D3 adjust keeps the standard based on past fights (e.g: E8S), but means that if a swap happens, there will be two melee on one side, and two ranged on the other, so the Dark Fire priorities get a little more complex.
- **Terminal Relativity**: Check your party's mitigation plan. 

### Approximate milestones

- **30%** HP at Advanced Relativity (when the boss becomes untargetable)

## English
```
{% include_relative macros/e12s_2.en.txt %}
```

## Japanese
```
{% include_relative macros/e12s_2.jp.txt %}
```

## Markers

*(These markers are the same as the Japanese markers from Part 1)*
![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"E12S P2",
  "MapID":759,
  "A":{"X":0.0,"Y":75.0,"Z":-85.0,"ID":0,"Active":true},
  "B":{"X":10.0,"Y":75.0,"Z":-75.0,"ID":1,"Active":true},
  "C":{"X":0.0,"Y":75.0,"Z":-65.0,"ID":2,"Active":true},
  "D":{"X":-10.0,"Y":75.0,"Z":-75.0,"ID":3,"Active":true},
  "One":{"X":7.071,"Y":75.0,"Z":-82.071,"ID":4,"Active":true},
  "Two":{"X":7.071,"Y":75.0,"Z":-67.929,"ID":5,"Active":true},
  "Three":{"X":-7.071,"Y":75.0,"Z":-67.929,"ID":6,"Active":true},
  "Four":{"X":-7.071,"Y":75.0,"Z":-82.071,"ID":7,"Active":true}
}
```

</details>

## Advanced Relativity

![](images/advanced_relativity.jpg)

## Timeline

![](https://i.redd.it/kitnqysrq2761.png)
*(Credit: [u/Syldris](https://www.reddit.com/r/ffxiv/comments/kj03t5/e12s_part_ii_timeline_image/))*