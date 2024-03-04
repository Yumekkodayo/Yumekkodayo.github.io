---
layout: default
title: P8S P2
parent: 零式レイド
nav_order: "08_2"
grand_parent: 6.0 暁月のフィナーレ
permalink: /6.0_endwalker/savage_raids/p8s_2/
---

# Abyssos: The Eighth Circle (Savage) - Part 2

PF uses Nukemaru's strat, with [Hydi/Bijyon's strat for Limitless Desolation](#limitless-desolation). The combination is often nicknamed "**Nukehai**" (ぬけはい).

{% include youtube.html id="67mpAI3O6Ys" %}
*(English subtitled)*

### Approximate milestones

- **40%** HP when the boss finishes casting Ego Death.

## Japanese

The following is [Game8's macro](https://game8.jp/ff14/480771) for the Nukehai strat.

*(Nukemaru's strat, Hydi/Bijyon's Limitless Desolation)*
```
{% include_relative macros/p8s_2.jp.txt %}
 ```
 
## English:

The following is my interpretation of Game8's macro, with some parts edited to fit the chat window and for clarity.

*(Nukemaru's strat, Hydi/Bijyon's Limitless Desolation)*
```
{% include_relative macros/p8s_2.en.txt %}
```

## Markers:

- `1` and `2` are for the two Sigil players during Natural Alignment's Ice/Fire.
- `ABC` is for αβγ in High Concept
- `D` demarcates the center line for the two stacks in High Concept.

![](images/markers.jpg)
![](images/markers_2.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"P8S P2 (Nukemaru)",
  "MapID":884,
  "A":{"X":100.0,"Y":0.0,"Z":81.5,"ID":0,"Active":true},
  "B":{"X":118.5,"Y":0.0,"Z":100.0,"ID":1,"Active":true},
  "C":{"X":100.0,"Y":0.0,"Z":118.5,"ID":2,"Active":true},
  "D":{"X":81.5,"Y":0.0,"Z":100.0,"ID":3,"Active":true},
  "One":{"X":100.0,"Y":0.0,"Z":85.0,"ID":4,"Active":true},
  "Two":{"X":100.0,"Y":0.0,"Z":95.0,"ID":5,"Active":true},
  "Three":{"X":90.0,"Y":0.0,"Z":90.0,"ID":6,"Active":true},
  "Four":{"X":110.0,"Y":0.0,"Z":90.0,"ID":7,"Active":true}
}
```

</details>

## Timeline
![](https://preview.redd.it/56gvxngdqj6a1.png?width=1780&format=png&auto=webp&s=1ca2a01ee6f82e07ba3ba679088f7cd0861e15db)
*(Credit: [u/ExiaKuromonji](https://www.reddit.com/r/ffxiv/comments/xa6me7/p8s_part_2_timeline/))*

## Nukemaru's Natural Alignment

Here's a breakdown for the Fire/Ice portion in Nukemaru's Natural Alignment.

<table>
  <tr>
    <td><p>These are the base positions for all players during Natural Alignment.</p><p>Two players of the same role (T/H vs DPS) will be selected as the <b>Sigils</b> (the players with the purple mark), forcing the remaining six players into a 2-4 or a 4-2 split.</p></td>
    <td><img src="images/natural_alignment.jpg"></td>
  </tr>
</table>

**Fire** is baited by the three <b>furthest</b> players from the Sigil.

- The side with 4 players take up their base positions as above.
- The side with 2 players have to figure out the priority between themselves to see who baits Fire:
```
Inside: MT>ST>H1>H2: Outside (baits Fire)
Inside: D1>D2>D3>D4: Outside (baits Fire)
```
<table>
  <tr>
    <td><p><b>Example 1:</b> MT and ST are selected as the Sigils.</p>
    <p>The remaining pairs are:<ul><li>H1 > H2</li><li>D1 > D2</li><li>D3 > D4</li></ul>In each pair, the player with the lower priority baits Fire (H2, D2, D4).</p><p><em>Notice H1 and H2 are baiting Fire in the front of the row.</em></p></td>
    <td><img src="images/natural_alignment_ex1_fire.jpg"></td>
  </tr>
  <tr>
    <td><p><b>Example 2:</b> D1 and D4 are selected as the Sigils.</p>
    <p>The remaining pairs are:<ul><li>MT > ST</li><li>H1 > H2</li><li>D2 > D3</li></ul>In each pair, the player with the lower priority baits Fire (ST, H2, D3).</p></td>
    <td><img src="images/natural_alignment_ex2_fire.jpg"></td>
  </tr>
</table>

**Ice** is baited by the two **closest** players to the Sigil.

- Because the party is split 2-4 or 4-2, one of the players in the group of 4 will have to move to the other group to make it an even 3-3 split. This will **either** be the MT (if T/H have four players), or D1 (if DPS have four players)
- The melee pair from the side that has four players (MT+ST, or D1+D2) baits Ice.

<table>
  <tr>
    <td><p><b>Example 1:</b> MT and ST are selected as the Sigils.</p>
    <p><ul><li>The DPS side has four players, so D1 moves to the other side.</li><li>D1 and D2 bait Ice.</li></ul></p></td>
    <td><img src="images/natural_alignment_ex1_ice.jpg"></td>
  </tr>
  <tr>
    <td><p><b>Example 2:</b> D1 and D4 are selected as the Sigils.</p>
    <p><ul><li>The T/H side has four players, so MT moves to the other side.</li><li>MT and ST bait Ice.</li></ul></p></td>
    <td><img src="images/natural_alignment_ex2_ice.jpg"></td>
  </tr>
</table>

## Nukemaru's High Concept #1

<table>
  <tr>
    <td><p>Note that the colour combinations are fixed.</p>
    <p><ul>
      <li>Green = α + β</li>
      <li>Blue = α + γ</li>
      <li>Purple = β + γ</li>
    </ul></p>
    </td>
    <td><img src="images/animal_concepts.jpg"></td>
  </tr>
</table>

This is Nukemaru's strat for High Concept #1. Note that αβγ are placed at **cardinal** positions instead of intercardinals, allowing players to naturally determine their North-South priorities when resolving various parts of High Concept.

<table>
  <tr>
    <td><p><b>1.</b> All players take up their starting positions.</p>
    <p><ul><li><b>7αβγ:</b> North, East, South respectively.</li><li><b>2-man stack + 27α:</b> 1/2 a tile north of West.</li><li><b>3-man stack + 27β + 27γ:</b> 1/2 a tile south of West.</li></ul></p></td>
    <td><img src="images/high_concept_1_ex1_1.jpg"></td>
  </tr>
  <tr>
    <td><b>2.</b> AoEs resolve.</td>
    <td><img src="images/high_concept_1_ex1_2.jpg"></td>
  </tr>
  <tr>
    <td><p><b>3.</b> Two coloured towers spawn. Everyone gather up for heals.</p>
    <p><ul><li><b>7αβγ:</b> If you need to fuse, meet in the center to create the animal concept.</li></ul></p><p><em>In this example, the towers are purple, so 7β and 7γ will fuse.</em></p></td>
    <td><img src="images/high_concept_1_ex1_3.jpg"></td>
  </tr>
  <tr>
    <td><p><b>4.</b> The boss will cleave one half of the arena.</p><p>Once the two players have created the animal concept, they split to take the two towers while dodging the boss's AoE.</p><p><b>If you came from the top side, you will take the top tower.</b></p><p><em>In this example, 7β came from above 7γ, so 7β takes the north tower. The boss is also cleaving east here.</em></p></td>
    <td><img src="images/high_concept_1_ex1_4.jpg"></td>
  </tr>
  <tr>
    <td>
      <p><b>5.</b> After the cleave goes off, everyone takes up position for the second set of AoEs.</p>
      <p>
        <ul>
          <li><b>27αβγ:</b> North, East, South respectively.</li>
          <li><b>7αβγ:</b>
            <ul>
              <li><b>If you fused:</b> Go 1/2 tile north/south of west. <b>If you came from the top side, you will take the northern position.</b></li>
              <li><b>If you did not fuse:</b> Return to your original starting position.</li>
            </ul>
          </li>
          <li><b>2-man and 3-man stacks:</b> Replace the two players that fused earlier. <b>The 2-man stack replaces the "more north" player.</b></li>
        </ul>
      </p>
      <p><em>In this example:
        <ul>
          <li>7α did not fuse earlier, so they return North.</li>
          <li>7β and 7γ fused:
            <ul>
              <li>7β goes west and takes the north position.</li>
              <li>7γ goes west and takes the south position.</li>
              <li>The 2-man stack takes 7β's position (east).</li>
              <li>The 3-man stack takes 7γ's position (south).</li>
            </ul>
          </li>
        </ul>
      </em></p>
    </td>
    <td><img src="images/high_concept_1_ex1_5.jpg"></td>
  </tr>
  <tr>
    <td><b>6.</b> Second round of AoEs resolve.</td>
    <td><img src="images/high_concept_1_ex1_6.jpg"></td>
  </tr>
  <tr>
    <td><p><b>7.</b> Four coloured towers spawn.</p>
    <p><b>If you need to fuse:</b>
      <ul>
        <li><b>27αβγ:</b> Go between the two north towers.</li>
        <li><b>Others:</b> Go between the two south towers.</li>
      </ul>
    </p>
    <p><em>In this example, the towers are blue, so the players at α and γ will fuse.
      <ul>
        <li>27α fuses with 27γ north.</li>
        <li>The players that <b>were</b> with 27α and 27γ fuse south.</li>
      </ul></em>
    </p></td>
    <td><img src="images/high_concept_1_ex1_7.jpg"></td>
  </tr>
  <tr>
    <td><p><b>8.</b> The boss will cleave one half of the arena again.</p><p>Once each pair have created the animal concept, they split to take the two towers while dodging the boss's AoE.</p><p><b>The player that came from the top side takes the top tower.</b></p><p><em>In this example:<ul><li>The two players that came from α take the top towers</li><li>The two players that came from γ take the bottom towers.</li><li>The boss is cleaving west.</li></ul></em></p></td>
    <td><img src="images/high_concept_1_ex1_8.jpg"></td>
  </tr>
</table>

## Limitless Desolation:

Hydi Ai and [Bijyon](https://youtu.be/GA3IWJde15g) proposes the following strategy for Limitless Desolation.

It takes advantage of the fact that the first and third set of towers always spawn in the top two rows, while the second and fourth set of towers always spawn in the middle two rows.

Nukemaru also made a guide explaining the strat:

{% include youtube.html id="8kdGUhXYBJI" %}

## Nukemaru's High Concept #2

This is Nukemaru's strat for High Concept #2. Several concepts from High Concept #1 carry over to High Concept #2.

<table>
  <tr>
    <td><p><b>1.</b> All players take up their starting positions.</p>
    <p>
      <ul>
        <li><b>7αβγ:</b> North, East, South respectively.</li>
        <li><b>27αβγ:</b>
          <ul>
            <li><b>Solo stack:</b> 1/2 a tile north of West.</li>
            <li><b>Other 27αβγ:</b> 1/2 a tile south of West <em>(one of the two remaining 27αβγ will be a 2-man stack)</em>.</li>
          </ul>
        </li>
        <li><b>No debuff:</b> North <em>(these will be two T/H or two DPS).</em></li>
      </ul>
    </p>
    <p><em>In this example, 27β has the solo stack.</em></p></td>
    <td><img src="images/high_concept_2_ex1_1.jpg"></td>
  </tr>
  <tr>
    <td><b>2.</b> AoEs resolve.</td>
    <td><img src="images/high_concept_2_ex1_2.jpg"></td>
  </tr>
  <tr>
    <td><p><b>3.</b> Two coloured towers spawn.</p>
    <p><ul>
        <li><b>7αβγ:</b> If you need to fuse, meet in the center to create the animal concept, just like High Concept #1.</li>
        <li><b>No debuff:</b> Fuse together North-West to make Ifrit.</li>
      </ul>
      <p>Ifrit players will suffer from continuous DoT damage until the end of High Concept, and need to be kept alive by the healers until then.</p>
      <p><b>Note that 7γ will <em>always</em> be involved in this fusion.</b></p>
      </p><p><em>In this example, the towers are purple, so 7β and 7γ will fuse.</em></p></td>
    <td><img src="images/high_concept_2_ex1_3.jpg"></td>
  </tr>
  <tr>
    <td><p><b>4.</b> The boss will cleave one half of the arena.</p><p><b>Merge Ifrit before dodging the cleave.</b></p><p>Once the two players have created the animal concept, they split to take the two towers while dodging the boss's AoE.</p><p><b>If you came from the top side, you will take the top tower.</b></p><p><em>In this example, 7β came from above 7γ, so 7β takes the north tower. The boss is also cleaving east here.</em></p></td>
    <td><img src="images/high_concept_2_ex1_4.jpg"></td>
  </tr>
  <tr>
    <td>
      <p><b>5.</b> After the cleave goes off, everyone takes up position for the second set of AoEs.</p>
      <p>
        <ul>
          <li><b>27αβγ:</b> North, East, South respectively.</li>
          <li><b>7αβγ:</b> The one that did <b>not</b> fuse earlier returns to their original starting position.</li>
          <li><b>Ifrits + Animal Concepts:</b> Take up the "T-shape" formation as shown. <b>If a healer is Ifrit, the healer should take the east Ifrit spot.</b></li>
        </ul>
      </p>
      <p><em>In this example, 7α did not fuse earlier, so they return North.</em></p>
    </td>
    <td><img src="images/high_concept_2_ex1_5.jpg"></td>
  </tr>
  <tr>
    <td><b>6.</b> Second round of AoEs resolve.</td>
    <td><img src="images/high_concept_2_ex1_6.jpg"></td>
  </tr>
  <tr>
    <td><p><b>7.</b> Four coloured towers spawn, along with four shades at the four cardinal directions.</p>
    <p>
      <ul>
        <li><b>Ifrits + Animal Concepts:</b> Split up in your formation, and tether to one shade each.</li>
        <li><b>27αβ:</b> Go between the two north towers.</li>
        <li><b>27γ + Unused 7αβ:</b> Go between the two south towers.</li>
      </ul>
    </p>
    <p><em>In this example, 7α was not used in the first fusion, so they will go south to fuse with 27γ.</em></p></td>
    <td><img src="images/high_concept_2_ex1_7.jpg"></td>
  </tr>
  <tr>
    <td><p><b>8.</b> The shades will each fire a beam in the direction of the player they were tethered to.</p>
    <p>
      <ul>
        <li><b>Ifrits + Animal Concepts:</b> Rotate clockwise to drag your tethered shade along the outer row/column.
        <ul>
          <li>The four corners of the arena <b>will not be safe</b>, because they will get hit by two beams.</li>
        </ul></li>
        <li>Each pair in the center needs to take the corresponding pair of coloured towers in the center four tiles. Note that the coloured towers will be in a <b>random configuration</b>.
          <ul>
            <li>The player that came from the northern side prioritizes the <b>North, then West tower</b> if there is a tie.</li>
          </ul>
        </li>
      </ul>
    </p>
    <p><em>In this example, 27α prioritizes north over 27β, and 7α prioritizes north over 27γ.</em></p></td>
    <td><img src="images/high_concept_2_ex1_8.jpg"></td>
  </tr>
  <tr>
    <td><p><b>9.</b> The two Ifrit players then combine with the two birds in the center to form four Phoenix feathers.</p><p>The four Phoenix feathers will then tether together and fuse to form Phoenix, which gives the Phoenix concept to all players in the party.</p><p><b>All party members must be topped to 100% HP before this final Phoenix fusion completes.</b></p></td>
    <td><img src="images/high_concept_2_ex1_9.jpg"></td>
  </tr>
</table>

## Frequently Asked Questions

<details markdown=block>
<summary><b>[High Concept 1]</b> Can both sets of towers be the same colour?</summary>
<table>
  <tr><td><p>Yes, the two sets of towers in High Concept 1 are not related to one another.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[High Concept 2]</b> Why is 7γ missing in the macro where it says "27γ/Unused 7αβ→Synthesize South"?</summary>
<table>
  <tr><td><p>The ultimate goal in High Concept 2 is to produce the Phoenix concept, which is done by merging two Ifrits with the two (green) birds, which are formed by combining α and β.</p><p>If the first set of towers <em>were green</em>, then players would just form two birds and immediately fuse them with the two Ifrits to make Phoenix at the first set of fusions.</p><p>Hence there cannot be any green towers in the first set, which means 7γ is always used.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[High Concept 2]</b> Why is 7γ always used in the first fusion?</summary>
<table>
  <tr><td><p>The ultimate goal in High Concept 2 is to produce the Phoenix concept, which is done by merging two Ifrits with the two (green) birds, which are formed by combining α and β.</p><p>If the first set of towers <em>were green</em>, then players would just form two birds and immediately fuse them with the two Ifrits to make Phoenix at the first set of fusions.</p><p>Hence there cannot be any green towers in the first set, which means 7γ is always used.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[High Concept 2]</b> Why are the first set of towers always purple or blue, and never green?</summary>
<table>
  <tr><td><p>The ultimate goal in High Concept 2 is to produce the Phoenix concept, which is done by merging two Ifrits with the two (green) birds, which are formed by combining α and β.</p><p>If the first set of towers <em>were green</em>, then players would just form two birds and immediately fuse them with the two Ifrits to make Phoenix at the first set of fusions.</p><p>Thus, the first set of towers cannot be green, and are therefore either purple or blue.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[High Concept 2]</b> Why should you create Ifrit first, before dodging the boss's E/W cleave?</summary>
<table>
  <tr><td><p>The problem is that if a healer needs to combine to conceptualize Ifrit, they need to top up the party before the second set of AoEs.</p><p>Ifrit cannot be merged in the center, as that spot is being used to merge the two tower players.</p><p>By delaying the merge to after the cleave, you prevent the healer from going to the center to top up the party to prepare for the second set of AoEs- by the time Ifrit merges and the healer can go mid, the party would have likely spread out and be out of range of healing.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Dominion]</b> Why is the tower order in Dominion D4321 instead of D1234?</summary>
<table>
  <tr><td><p>Earlier macros had D1234- the problem is that RDM is the only DPS that cannot heal/shield themselves off the GCD, and would often end up dying to the follow-up raid-wide damage. Casters also have the lowest max HP of all the DPS.</p><p>Putting the casters next to the healers in the priority order increases the likelihood that they are in range of receiving healing.</p><p>Nukemaru's video guide also puts melees towards the outside and casters towards the center for the same reason, leading to the tanks > healers > D4321 order.</p></td></tr>
</table>
</details>