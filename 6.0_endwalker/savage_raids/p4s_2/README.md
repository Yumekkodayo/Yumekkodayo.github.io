---
layout: default
title: P4S P2
parent: 零式レイド
nav_order: "04_2"
grand_parent: 6.0 暁月のフィナーレ
permalink: /6.0_endwalker/savage_raids/p4s_2/
---

# Asphodelos: The Fourth Circle (Savage) - Part 2

PF uses [Inumaru's strat](https://youtu.be/1sfnBHXf2nA) (essentially identical to the Idyllshire strat, except for Act 3), with the following modifications:

- **Japanese** parties will do Inumaru's strat for Act3.
- **English** parties will do Xeno's strat for Act 3.
- Curtain Call timings are flipped from Inumaru's video:
  - Tanks/Healers cut their tethers at 6 seconds remaining.
  - DPS cut theirs at 11 seconds remaining.

## English

English parties will do Xeno's strat for Act 3.
```
{% include_relative macros/p4s_2_xeno.en.txt %}
```

<details markdown=block>
<summary>Japanese translation</summary>

```
{% include_relative macros/p4s_2_xeno.jp.txt %}
```

</details>

## Japanese

Japanese parties will do Inumaru's strat for Act 3.
```
{% include_relative macros/p4s_2_inumaru.jp.txt %}
```

<details markdown=block>
<summary>English translation</summary>

```
{% include_relative macros/p4s_2_inumaru.en.txt %}
```

</details>

## Markers

- `1234` are for towers
- `ABCD` are for resolving fire stacks in Act 2 (they won't line up with the thorns).

The markers also indicate the tether order for Act 4. Of note, 1234 overlap the white triangles on the floor.

![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"P4S P2",
  "MapID":801,
  "A":{"X":105.0,"Y":0.0,"Z":85.0,"ID":0,"Active":true},
  "B":{"X":115.0,"Y":0.0,"Z":105.0,"ID":1,"Active":true},
  "C":{"X":95.0,"Y":0.0,"Z":115.0,"ID":2,"Active":true},
  "D":{"X":85.0,"Y":0.0,"Z":95.0,"ID":3,"Active":true},
  "One":{"X":98.5,"Y":0.0,"Z":81.5,"ID":4,"Active":true},
  "Two":{"X":118.5,"Y":0.0,"Z":98.5,"ID":5,"Active":true},
  "Three":{"X":101.5,"Y":0.0,"Z":118.5,"ID":6,"Active":true},
  "Four":{"X":81.5,"Y":0.0,"Z":101.5,"ID":7,"Active":true}
}
```

</details>

## Act 2

Elemental uses the [Idyllshire Act 2 strat](https://youtu.be/1sfnBHXf2nA?t=278).

To begin, the boss will telegraph two sets of tethers. Each set triggers two opposite towers, and two opposite AoEs.

Pay attention to which pair of **towers** get triggered first- that determines where the party moves.

<table>
  <th></th>
  <th style="text-align:center">N/S towers first</th>
  <th style="text-align:center">E/W towers first</th>
  <tr>
    <td width="34%"><p><b>1.</b> Break AoEs, break Dark tether</p><ul><li><b>Dark (no orb) Tank:</b> Always NW.</li><li><b>Dark Healer:</b> Always SE.</li><li><b>Fire DPS:</b> Identify your Fire partner and priority for later.</li><li><b>Everybody except Dark Tank/Healer:</b> Stack middle.</li></ul></td>
	<td width="33%"><img src="images/act_2_1a.jpg"></td>
  <td><img src="images/act_2_1b.jpg"></td>
  </tr>
  <tr>
    <td><p><b>2.</b> After baiting AoEs, everyone moves into position for the first set of mechanics.</p><ul><li>Dark Tank/Healer always get towers.</li><li>Fire Tank + Healer break their tether.</li></ul></td>
	<td width="33%"><img src="images/act_2_2a.jpg"></td>
  <td><img src="images/act_2_2b.jpg"></td>
  </tr>
  <tr>
    <td><p><b>3.</b> First set of towers and fire stacks resolve.</p></td>
	<td width="33%"><img src="images/act_2_3a.jpg"></td>
  <td><img src="images/act_2_3b.jpg"></td>
  </tr>
  <tr>
    <td><p><b>4.</b> Everyone moves in for healing, then moves to prepare for the second set of mechanics:</p><ul><li><b>Healers:</b> Rotate <b>clockwise</b></li><li><b>Dark Tank:</b> Rotate <b>clockwise</b> to the next tower.</li><li><b>Fire Tank:</b> Rotate <b>anti-clockwise</b> to the next stack.</li><li><b>Fire DPS:</b> Break your tether.</li></ul><p>Everyone rotates clockwise <em>except</em> the Fire Tank and the Fire DPS in the following priority:</p><p style="text-align:center"><b>cw:</b> D1 > D2 > D3 > D4 <b>:ccw</b></p></td>
	<td width="33%"><img src="images/act_2_4a.jpg"></td>
  <td><img src="images/act_2_4b.jpg"></td>
  </tr>
  <tr>
    <td><p><b>5.</b> Second set of towers and fire stacks resolve.</p></td>
	<td width="33%"><img src="images/act_2_5a.jpg"></td>
  <td><img src="images/act_2_5b.jpg"></td>
  </tr>
</table>


## Act 3

Note that English and Japanese groups will do different Act 3 strats.

- English groups will use Xeno's Act 3.
  - Tanks/Melee and Healers/Ranged alternate taking towers + Earthshakers.
- Japanese groups will use [Inumaru's Act 3](https://youtu.be/1sfnBHXf2nA?t=627).
  - Tanks/Melee take all Earthshakers. Healers/Ranged take all towers.

## Timeline

![](https://preview.redd.it/tskvunw5vvb81.png?width=3200&format=png&auto=webp&s=ca69a6132e5aac040f4afd7c21c55bfa6a95c860)
*(Credit: [u/Syldris](https://www.reddit.com/r/ffxiv/comments/s3yfu8/p4s_rotation_and_timeline/))*