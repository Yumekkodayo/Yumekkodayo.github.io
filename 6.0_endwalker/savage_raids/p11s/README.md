---
layout: default
title: P11S
parent: Savage Raids
nav_order: "11"
grand_parent: 6.0 Endwalker
permalink: /6.0_endwalker/savage_raids/p11s/
---

# Anabaseios: The Eleventh Circle (Savage)

[Game8](https://game8.jp/ff14/532825) is using an updated version of Hamkatsu's strat, with ZizieZip's updated Light and Darkness strat.

{% include youtube.html id="-EM-XR6qocU" %}

### Things to check on Party Finder

- Check the Shadowed Messengers strat:
  - **Japanese** parties will begin Shadowed Messengers with the boss facing true West. This results in two movements while dodging all the AoEs, but doesn't rely on the MT looking for the Light clone.
  - **English** groups will have the MT face the boss towards the Light clone (or directly opposite), resulting in one less movement from the dodge.
- Check who adjusts for (Dark) Jury Overruling:
  - **Japanese** parties will generally stick to the macro and have the DPS rotate clockwise to their respective T/H partners.
  - **English** parties *may* opt to have the T/H rotate anti-clockwise to join their DPS partners instead.

### English

```
{% include_relative macros/p11s.en.txt %}
```

### Japanese

```
{% include_relative macros/p11s.jp.txt %}
```

## Markers

The colours indicate the pairs positions (MT/D3 are on red, etc).

![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"P11S",
  "MapID":941,
  "A":{"X":100.0,"Y":0.0,"Z":87.0,"ID":0,"Active":true},
  "B":{"X":113.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},
  "C":{"X":100.0,"Y":0.0,"Z":113.0,"ID":2,"Active":true},
  "D":{"X":87.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},
  "One":{"X":90.8,"Y":0.0,"Z":90.8,"ID":4,"Active":true},
  "Two":{"X":109.2,"Y":0.0,"Z":90.8,"ID":5,"Active":true},
  "Three":{"X":109.2,"Y":0.0,"Z":109.2,"ID":6,"Active":true},
  "Four":{"X":90.8,"Y":0.0,"Z":109.2,"ID":7,"Active":true}
}
```

</details>

You may see the square markers rotated 90 degrees clockwise in Japanese parties.

![](images/markers2.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"P11S (JP)",
  "MapID":941,"A":{"X":100.0,"Y":0.0,"Z":87.0,"ID":0,"Active":true},
  "B":{"X":113.0,"Y":0.0,"Z":100.0,"ID":1,"Active":true},
  "C":{"X":100.0,"Y":0.0,"Z":113.0,"ID":2,"Active":true},
  "D":{"X":87.0,"Y":0.0,"Z":100.0,"ID":3,"Active":true},
  "One":{"X":109.2,"Y":0.0,"Z":90.8,"ID":4,"Active":true},
  "Two":{"X":109.2,"Y":0.0,"Z":109.2,"ID":5,"Active":true},
  "Three":{"X":90.8,"Y":0.0,"Z":109.2,"ID":6,"Active":true},
  "Four":{"X":90.8,"Y":0.0,"Z":90.8,"ID":7,"Active":true}
}
```

</details>

## Timeline
![](https://preview.redd.it/rm6mpxvwhh3b1.png?width=1796&format=png&auto=webp&v=enabled&s=916f64761d5fb5770f590329c1b41cdfc0619b21)
*(Credit: [u/ExiaKuromonji](https://www.reddit.com/r/ffxiv/comments/13xvne7/spoiler_64_p11s_timeline_and_abilities/))*

## ZizieZip's Dark and Light

During Dark and Light, the boss will tether the party together with two solid tethers (one light, one dark), and two split tethers (light on one side, and dark on the other).

The boss will then go through the basic mechanics of the fight, which need to be resolved together with the tethers.

The party will always rotate **clockwise** to resolve the upcoming mechanics.

<table>
  <tr>
    <td width="50%"><p><b>1.</b> Preposition based on your roles:</p>
    <ul><li><b>Tanks/Healers:</b> West</li><li><b>DPS:</b> East</li></ul>
    <p>Players will get tethered together.</p>
    <ul>
      <li>Single-coloured tethers:
        <ul>
          <li>One tank and one DPS (light)</li>
          <li>One healer and one DPS (dark)</li>
        </ul>
      </li>
      <li>Split tethers:
        <ul>
          <li>One tank (dark) and one DPS (light)</li>
          <li>One healer (light) and one DPS (dark)</li>
        </ul>
      </li>
    </ul>
    We want to <b>keep the single-coloured tethers long, and the split tethers short.</b></td>
    <td><img src="images/dark_and_light_01.jpg"></td>
  </tr>
  <tr>
    <td><p><b>2.</b> If you are connected to a <b>purple tether</b> (dark), <b>swap sides</b>.</p>
    <p>This is equivalent to:</p>
    <ul>
      <li><b>Tanks/Healers:</b>
        <ul>
          <li><b>Light:</b> West</li>
          <li><b>Dark:</b> East</li>
        </ul>
      </li>
      <li><b>DPS:</b>
        <ul>
          <li><b>Light:</b> East</li>
          <li><b>Dark:</b> West</li>
        </ul>
      </li>
    </ul>
    </td>
    <td><img src="images/dark_and_light_02.jpg"></td>
  </tr>
  <tr>
    <td><p><b>3.</b> The boss will cast Arcane Revelation, and glow either light (yellow) or dark (purple).</p><p>Note which colour the boss glowed.</p></td>
    <td><img src="images/dark_and_light_03.jpg"></td>
  </tr>
  <tr>
    <td><p><b>4.</b> Orbs will appear at the cardinal locations.</p><p>Rotate <b>clockwise</b> if needed so that you are standing at the <b>opposite</b> coloured orb to whatever the boss glowed in the previous step.</p></td>
    <td><img src="images/dark_and_light_04.jpg"></td>
  </tr>
  <tr>
    <td><p><b>5.</b> The boss then casts Jury Overruling (glowing light or dark), requiring the party to spread.</p>
    <p><em>(The players will alternate between light and dark.)</em></p>
    <p>From the stack positions in the previous step:</p>
    <ul>
      <li><b>Long Light:</b> Stay where you are.</li>
      <li><b>Long Dark:</b> Rotate clockwise once (45 degrees).</li>
      <li><b>Short Light:</b> Rotate clockwise twice (90 degrees).</li>
      <li><b>Short Dark:</b> Rotate clockwise three times (135 degrees).</li>
    </ul>
    <p>The long tethers can use the waymarks on the ground.</p><p>The short tethers will use the diamond marks on the floor inside the boss's targeting circle.</p></td>
    <td><img src="images/dark_and_light_05.jpg"></td>
  </tr>
  <tr>
    <td><p><b>6.</b> Resolve the second half of Jury Overruling based on whether the boss is aspected to Light or Dark.</p></td>
    <td><img src="images/dark_and_light_06a.jpg"><img src="images/dark_and_light_06b.jpg"></td>
  </tr>
  <tr>
    <td><p><b>7.</b> Reset your positions on opposite markers.</p><p>The boss will then cast Divisive Overruling.</p></td>
    <td><img src="images/dark_and_light_07.jpg"></td>
  </tr>
  <tr>
    <td><p><b>8.</b> Rotate 90 degrees <b>clockwise</b> to dodge the first part of Divisive Overruling.</p></td>
    <td><img src="images/dark_and_light_08.jpg"></td>
  </tr>
  <tr>
    <td><p><b>9.</b> Resolve the second part of Divisive Overruling based on whether the boss is aspected to Light or Dark.</p>
    <ul><li>If the boss is <b>Light:</b> Stack in your light parties.</li>
    <li>If the boss is <b>Dark:</b>
      <ul>
        <li><b>Short tethers:</b> Rotate <b>clockwise</b>.</li>
        <li><b>Long tethers:</b> Rotate <b>anti-clockwise</b>.</li>
      </ul>
    </li></ul></td>
    <td><img src="images/dark_and_light_09a.jpg">
    <img src="images/dark_and_light_09b.jpg"></td>
  </tr>
</table>

## Frequently Asked Questions

<details markdown=block>
<summary><b>[Damage Down]</b> How strong is the damage down debuff in this fight?</summary>
<table>
  <tr><td><p>The Damage Down debuff in this phase lowers a player's damage by <b>39%</b>.</p></td></tr>
</table>
</details>
<details markdown=block>
<summary><b>[Letter of the Law]</b> Why is the split N/E vs S/W, and not N/W vs S/E like before?</summary>
<table>
  <tr><td><p>This is because the logic is "from your base positions, rotate clockwise as needed".</p><p>For most other mechanics, the base positions are E/W, which means the MT group takes W or N, while the ST group takes E or S.</p><p>With Letter of the Law, the "natural" position there (supposedly) is the usual "tanks North, party South". By then applying the same logic above, you then get "tanks N or E, party S or W".</p></td></tr>
</table>
</details>