---
layout: default
title: A12S
parent: Savage Raids
nav_order: "12"
grand_parent: 3.0 Heavensward
permalink: /3.0_heavensward/savage_raids/a12s/
---

# Alexander - The Eyes of the Creator (Savage)

This is [Cien Choco's macro](https://jp.finalfantasyxiv.com/lodestone/character/1622544/blog/3194463/) for Pekoelog's strat.

Pekoelog:
  - [Part 1](https://pekoe1001.blog.shinobi.jp/Entry/1585/)
  - [Part 2](https://pekoe1001.blog.shinobi.jp/Entry/1586/)

## Japanese

```
{% include_relative macros/a12s.jp.txt %}
```

## English

```
{% include_relative macros/a12s.en.txt %}
```

## Markers

At the time, only the `ABC` markers were available.

Now that more markers are available, I would place the markers as below. The `A` marker is hidden behind the boss.

"South-left" would be the `1` marker, while "South-right" would be the `2` marker.

`ABD` are used for Defamation during Temporal Stasis.
`12` are used for Shared Sentence and Aggravated Assault during Temporal Stasis.

![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"A12S",
  "MapID":193,
  "A":{"X":0.0,"Y":400.0,"Z":-24.5,"ID":0,"Active":true},
  "B":{"X":24.5,"Y":400.0,"Z":0.0,"ID":1,"Active":true},
  "C":{"X":0.0,"Y":0.0,"Z":0.0,"ID":2,"Active":false},
  "D":{"X":-24.5,"Y":400.0,"Z":0.0,"ID":3,"Active":true},
  "One":{"X":-5.0,"Y":400.0,"Z":24.7,"ID":4,"Active":true},
  "Two":{"X":5.0,"Y":400.0,"Z":24.7,"ID":5,"Active":true},
  "Three":{"X":0.0,"Y":0.0,"Z":0.0,"ID":6,"Active":false},
  "Four":{"X":0.0,"Y":0.0,"Z":0.0,"ID":7,"Active":false}
}
```

</details>