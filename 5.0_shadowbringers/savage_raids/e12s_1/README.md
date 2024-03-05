---
layout: default
title: E12S P1
parent: 零式レイド
nav_order: "12_1"
grand_parent: 5.0 漆黒のヴィランズ
permalink: /5.0_shadowbringers/savage_raids/e12s_1/
---

# Eden's Promise: Eternity (Savage) - Part 1

The standard PF strat takes [Idyll strat (イディル式)](https://kanatan.info/archives/25637304.html) positions for Titan, but use [Akito's strat (あきと式)](https://youtu.be/hdLm1Q1BEWg) for Giants (巨人) and Lion. (Akito brings the boss down to the south edge and has the statue stacks north and south of the boss.)

### Things to check on Party Finder

- Check Shiva spread positions- some macros have the healers on the NW and SE diagonals.
- Decide which tank is going to Reprisal Obliterations, and which tank will Reprisal Diamond Dust and Earthern Fury.
- Sort out tank Invulns for the three Formless Judgments. If there is a PLD, they should Hallowed Ground the 2nd , and the other tank should Invuln the 1st and 3rd.

### Approximate milestones

- **54%** HP at the end of Titan phase (when the floor changes back).
- **23%** HP at the end of Lions (when the Lions disappear).

## English
```
{% include_relative macros/e12s_1.en.txt %}
```

## Japanese
```
{% include_relative macros/e12s_1.jp.txt %}
```

## Markers

There are two sets of markers used in PF, that are used for the Lions phase. 

**English** parties will put markers centered on the circle patterns on the ground.

Small lions are pointed to the center of the markers, while the big lion players dodge the fire cones in the center of the N/S markers (see image).
![](images/markers_en.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"E12S P1 (EN)",
  "MapID":759,
  "A":{"X":0.0,"Y":75.0,"Z":-86.3,"ID":0,"Active":true},
  "B":{"X":11.3,"Y":75.0,"Z":-75.0,"ID":1,"Active":true},
  "C":{"X":0.0,"Y":75.0,"Z":-63.7,"ID":2,"Active":true},
  "D":{"X":-11.3,"Y":75.0,"Z":-75.0,"ID":3,"Active":true},
  "One":{"X":8.43,"Y":75.0,"Z":-81.75,"ID":4,"Active":true},
  "Two":{"X":8.43,"Y":75.0,"Z":-68.25,"ID":5,"Active":true},
  "Three":{"X":-8.43,"Y":75.0,"Z":-68.25,"ID":6,"Active":true},
  "Four":{"X":-8.43,"Y":75.0,"Z":-81.75,"ID":7,"Active":true}
}
```

</details>

**Japanese** parties will put the markers aligned to the grid tiles on the ground.

Small lions are pointed towards specific corners of the square markers, while the big lion players dodge the fire cones by standing on the outer side of the N/S markers (see image).
![](images/markers_jp.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"E12S P1 (JP)",
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

## Primals/Titan phase

![](images/titan.jpg)

## Giants/巨人

The main way PF handles the giants is Akito's method or more commonly referred to as N/S giants (巨人南北):

**Akito/1A**: MT brings boss south, party stacks north and south. MT group stacks south, OT group stacks north (since the boss will be facing south)

## Akito TT Lion strat/ライオンAkitoTT式

Explanation (Japanese): [video](https://youtu.be/hdLm1Q1BEWg?t=657)

**Baiting small lions**: Where players stand to bait the small lions will depend on which markers you use (see marker images above).

**Baiting big lions**: The second and third big lion baits should not be all the way at the edge of the arena. The center of the lion is just under two tiles away from the edge of the arena.

If you go all the way to the edge of the arena to bait the second or third big lion, you are actually going further from the big lion, and the big lion will target the person standing at `A` or `C` instead. 
![](images/akito_lions.jpg)

## Timeline

![](https://i.redd.it/qknoduxviu661.png)
*(Credit: [u/Syldris](https://www.reddit.com/r/ffxiv/comments/khx7wr/e12s_part_i_timeline_image/))*