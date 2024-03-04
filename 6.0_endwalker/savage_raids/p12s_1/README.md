---
layout: default
title: P12S P1
parent: Savage Raids
nav_order: "12_1"
grand_parent: 6.0 Endwalker
permalink: /6.0_endwalker/savage_raids/p12s_1/
---

# Anabaseios: The Twelfth Circle (Savage) - Part 1

[Game8](https://game8.jp/ff14/534748) has gone along with Nukemaru's strategy for the fight:

{% include youtube.html id="hkCG_VH4sI4" %}
*(English subtitled)*

- Invuln Paradeigma 1
- 十-shaped Paradeigma 2
- Idyllshire's Paradeigma 3
- Neverland's Limit Cut

### Approximate milestones

- **Under 32%** when the boss disappears for Limit Cut.

### English

```
{% include_relative macros/p12s_1.en.txt %}
```

### Japanese

```
{% include_relative macros/p12s_1.jp.txt %}
```

## Markers

![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"P12S-1",
  "MapID":943,
  "A":{"X":100.0,"Y":0.0,"Z":82.0,"ID":0,"Active":true},
  "B":{"X":118.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},
  "C":{"X":100.0,"Y":0.0,"Z":118.0,"ID":2,"Active":true},
  "D":{"X":82.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},
  "One":{"X":110.0,"Y":0.0,"Z":90.0,"ID":4,"Active":true},
  "Two":{"X":110.0,"Y":0.0,"Z":110.0,"ID":5,"Active":true},
  "Three":{"X":90.0,"Y":0.0,"Z":110.0,"ID":6,"Active":true},
  "Four":{"X":90.0,"Y":0.0,"Z":90.0,"ID":7,"Active":true}
}
```

</details>

## Timeline
![](images/timeline.jpg)
*(Credit: [u/ExiaKuromonji](https://www.reddit.com/r/ffxiv/comments/141xz50/spoiler64_p12s_part_1_timeline_and_abilities/))*

## Superchain Theory 1

The debuffs applied during Superchain Theory 1 split the party into tanks/healers and DPS:

- One role is responsible for placing and resolving the aspected towers.
- The other role will spread for the Heavensflame AoEs.

Because of this, the movement after the third set of shapes is fixed:

<table>
  <tr>
    <th>Tanks + Healers Heavensflame, DPS towers</th>
    <th>DPS Heavensflame, Tanks + Healers towers</th>
  </tr>
  <tr>
    <td><img src="images/superchain_theory_01a.jpg"></td>
    <td><img src="images/superchain_theory_01b.jpg"></td>
  </tr>
</table>

## Limit Cut

Limit Cut can be broken into two parts- the first four dashes, and the last four dashes.

Within each block of four dashes, the center add will do a small 270-degree cleave in the middle twice, and fire two beams at the two closest players twice, **all in a random order**.

<table>
  <tr>
    <td width="50%"><p><b>1.</b> Athena appears at a random vertex and all players get numbered.</p><p>Take up your initial positions, <b>relative to Athena's position.</b></p>
    <ul>
      <li><b>2 and 4</b>: Note the starting position is not directly in front of Athena.</li>
      <li><b>5 and 7</b>: Start towards the center of the arena to prepare to bait the first pair of beams.</li>
    </ul></td>
    <td><img src="images/palladion_01.jpg"></td>
  </tr>
  <tr>
    <td><p><b>2. First set of four dashes.</b></p>
    <p>The add in the middle will begin a set of two cleaves, and two pairs of beams in a random order.</p>
    <p>The boss dashes 1.</p>
    <ul>
      <li><b>1 and 3:</b> Move just out of the residual fire puddle to prepare to bait 3's dash.</li>
      <li><b>2 and 4:</b> Move to stand along the edge to prepare to bait 2's dash.</li>
    </ul></td>
    <td><img src="images/palladion_02.jpg"></td>
  </tr>
  <tr>
    <td><p><b>3.</b> The boss dashes 2.</p>
    <ul>
      <li><b>2 and 4:</b> Move just out of the residual fire puddle to prepare to bait 4's dash.</li>
    </ul>
    <p>In this example, the center add now fires beams at the two closest players (5 and 7), but this could come earlier or later.</p><p>When 5 and 7 get hit by the beams, they move out to the edge, while the next pair of players (6 and 8) move in to prepare to bait the next set of beams.</p></td>
    <td><img src="images/palladion_03.jpg"></td>
  </tr>
  <tr>
    <td><p><b>4.</b> The boss dashes 3.</p>
    <ul>
      <li><b>1 and 3:</b> Move ahead of 5 and 7, and prepare to bait beams.</li>
      <li><b>5 and 7:</b> Stack together next to the fire puddle left behind by 1 and 3 to prepare for the stack.</li>
    </ul></td>
    <td><img src="images/palladion_04.jpg"></td>
  </tr>
  <tr>
    <td><p><b>5.</b> The boss dashes 4.</p>
    <ul>
      <li><b>2 and 4:</b> Move ahead of 6 and 8, and prepare to bait beams.</li>
      <li><b>6 and 8:</b> Stack together next to the fire puddle left behind by 2 and 4 to prepare for the stack.</li>
    </ul>
    <p>In this example, the center add now fires beams at the two closest players (6 and 8), but this could come earlier.</p><p>When 6 and 8 get hit by the beams, they move out to the edge, while the next pair of players (1 and 3) move in to prepare to bait the next set of beams.</p></td>
    <td><img src="images/palladion_05.jpg"></td>
  </tr>
  <tr>
    <td><p><b>6. Second set of four dashes.</b></p>
    <p>The add in the middle will begin another set of two cleaves, and two pairs of beams in a random order.</p>
    <p>The boss dashes 5.</p>
    <ul>
      <li><b>5 and 7:</b> Move just out of the residual fire puddle to prepare to bait 7's dash.</li>
    </ul>
    <p>As space is running out, 1 and 3 should try to move as far clockwise as they can to avoid 1's beam clipping 5 and 7.</p></td>
    <td><img src="images/palladion_06.jpg"></td>
  </tr>
  <tr>
    <td><p><b>7.</b> The boss dashes 6.</p>
    <p>The first fire puddle left behind when the boss dashed 1 will disappear.</p>
    <p>In this example, the center add now fires beams at the two closest players (1 and 3), but this could come earlier or later.</p><p>When 1 and 3 get hit by the beams, they move out to the edge, while the next pair of players (2 and 4) move in to prepare to bait the next set of beams.</p></td>
    <td><img src="images/palladion_07.jpg"></td>
  </tr>
  <tr>
    <td><p><b>8.</b> The boss dashes 7.</p>
    <p>The second fire puddle left behind when the boss dashed 2 will disappear.</p>
    <p>2 and 4 should try to move as far clockwise as they can to avoid 2's beam clipping 6 and 8.</p></td>
    <td><img src="images/palladion_08.jpg"></td>
  </tr>
  <tr>
    <td><p><b>9.</b> The boss dashes 8.</p>
    <p>In this example, the center add now fires beams at the two closest players (2 and 4), but this could happen earlier.</p>
    <p>All players move to (true) North to prepare for Theos's Ultima.</p></td>
    <td><img src="images/palladion_09.jpg"></td>
  </tr>
</table>

## Frequently Asked Questions

<details markdown=block>
<summary><b>[Damage Down]</b> How strong is the damage down debuff in this fight?</summary>
<table>
  <tr><td><p>The Damage Down debuff in this phase lowers a player's damage by <b>38%</b>.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Palladion (Limit Cut)]</b> Why does 2 and 4 resolve their stack along the edge, instead of at the vertex?</summary>
<table>
  <tr>
    <td width="50%"><p>Athena's dash deals damage based on how far she had to dash to get to the next player (players take extra damage if they are within a certain distance to Athena).</p><p>Putting 2 and 4 North results in this dash to 5 (and 7) being close enough to the previous player that 5 and 7 may now get killed as a result.</p></td>
    <td><img src="images/palladion_faq.jpg"></td>
  </tr>
</table>
</details>
<details markdown=block>
<summary><b>[Superchain Theory 2]</b> How am I still getting hit by the angel beams?</summary>
<table>
  <tr>
    <td width="50%"><p>The angel beams in the middle of Superchain Theory 2 do <em>not</em> split the arena into four columns of equal width.</p><p>As you can see from the diagram here, the beams are actually slightly displaced <em>(in this example, the party needed to dodge east)</em>.</p></td>
    <td><img src="images/superchain_theory_02.jpg"></td>
  </tr>
</table>
</details>