---
layout: default
title: Thordan EX
parent: 極討滅戦
nav_order: 3
grand_parent: 3.0 蒼天のイシュガルド
permalink: /3.0_heavensward/extreme_trials/thordan/
---

# The Minstrel's Ballad: Thordan's Reign

A more up-to-date reference would be Nukemaru's guide, which [Game8](https://game8.jp/ff14/557234) also featured:

{% include youtube.html id="MexDR_KSmZc" %}

---

## English
```
{% include_relative macros/thordan.en.txt %}
```

## Japanese
```
{% include_relative macros/thordan.jp.txt %}
```

---

## Markers

You can use markers in this fight, but they're not really needed as Thordan leaves his sword behind at true North for the parts where you have map-relative spreads.

- `ABCD` are for orientation.
- The `1` marker is for the marked healer at the first Knights of Round mechanic.

![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"Thordan EX",
  "MapID":91,
  "A":{"X":0.0,"Y":0.039,"Z":-19.0,"ID":0,"Active":true},
  "B":{"X":19.0,"Y":0.039,"Z":0.0,"ID":1,"Active":true},
  "C":{"X":0.0,"Y":0.039,"Z":19.0,"ID":2,"Active":true},
  "D":{"X":-19.0,"Y":0.039,"Z":0.0,"ID":3,"Active":true},
  "One":{"X":8.03,"Y":0.039,"Z":-17.22,"ID":4,"Active":true},
  "Two":{"X":0.0,"Y":0.0,"Z":0.0,"ID":5,"Active":false},
  "Three":{"X":0.0,"Y":0.0,"Z":0.0,"ID":6,"Active":false},
  "Four":{"X":0.0,"Y":0.0,"Z":0.0,"ID":7,"Active":false}
}
```
```json
{
  "Name":"Thordan Unreal",
  "MapID":963,
  "A":{"X":0.0,"Y":0.039,"Z":-19.0,"ID":0,"Active":true},
  "B":{"X":19.0,"Y":0.039,"Z":0.0,"ID":1,"Active":true},
  "C":{"X":0.0,"Y":0.039,"Z":19.0,"ID":2,"Active":true},
  "D":{"X":-19.0,"Y":0.039,"Z":0.0,"ID":3,"Active":true},
  "One":{"X":8.03,"Y":0.039,"Z":-17.22,"ID":4,"Active":true},
  "Two":{"X":0.0,"Y":0.0,"Z":0.0,"ID":5,"Active":false},
  "Three":{"X":0.0,"Y":0.0,"Z":0.0,"ID":6,"Active":false},
  "Four":{"X":0.0,"Y":0.0,"Z":0.0,"ID":7,"Active":false}
}
```

</details>

---

## Knights of Round #2 (4x towers)

The towers always spawn on the line perpendicular to the knight that spawns somewhere towards the outside of the arena.

Using that knight as north (N.B: *not* Thordan or the Dragon Eye), we assign the healers and ranged towers relative to that knight. Tanks and melee should fill in where possible.

![](images/towers.jpg)

---

## Notes

You don't *have* to destroy all the small Comet Circles during the Meteors phase- you can let one explode and still survive (it will deal a little over half the party's max HP).

If your party is struggling with this phase, you can choose to ignore the north Comet (which is easily recognisable via Thordan's sword just beside it).