---
layout: default
title: P8S P1
parent: Savage Raids
nav_order: "08_1"
grand_parent: 6.0 Endwalker
permalink: /6.0_endwalker/savage_raids/p8s_1/
---

# Abyssos: The Eighth Circle (Savage) - Part 1

### Things to check on Party Finder

- Note the spread positions are not the typical spread.
- Check the Gorgons 2 strat (colours vs Spriggan).

## FFO strat

PF and Game8 went along with the [FFO strat](https://jp.finalfantasyxiv.com/lodestone/character/17170591/blog/5094725/), named after the ["Final Fantasy Online" board on 5ちゃねる](https://egg.5ch.net/ffo/), where the strat was pieced together.

Nukemaru made a video specifically going over the FFO strat:

{% include youtube.html id="IRsYjJG-ab4" %}
*(English subtitled)*

The FFO strat resolves Gorgons 2 based on coloured markers. *Some* parties (particularly EN) will do "Spriggan Gorgons 2" instead *(see below)*

## Japanese

*(FFO strat, colour-coded Gorgons 2)*
```
{% include_relative macros/p8s_1.jp.txt %}
```

## English

*(FFO strat, colour-coded Gorgons 2)*
```
{% include_relative macros/p8s_1.en.txt %}
```

## FFO strat (with Spriggan Gorgons 2)

Some parties (particularly English groups) will do ["Spriggan Gorgons 2"](#spriggan-gorgons-fixed-positions) instead of the colour-coded style that Game8 proposes.

## English 

*(FFO strat, Spriggan Gorgons 2)*
```
{% include_relative macros/p8s_1_spriggan.en.txt %}
```

## Japanese

*(FFO strat, Spriggan Gorgons 2 - 蛇2回目固定式)*
```
{% include_relative macros/p8s_1_spriggan.jp.txt %}
```

## Markers

- 1 and A are for resolving Stomp Dead (using the L-stomp method)

![](images/markers.jpg)
<details markdown=block>
<summary>XIVLauncher WaymarkPresetPlugin positions</summary>

```json
{
  "Name":"P8S",
  "MapID":884,
  "A":{"X":100.0,"Y":0.0,"Z":91.6,"ID":0,"Active":true},
  "B":{"X":108.4,"Y":0.0,"Z":100.0,"ID":1,"Active":true},
  "C":{"X":100.0,"Y":0.0,"Z":108.4,"ID":2,"Active":true},
  "D":{"X":91.6,"Y":0.0,"Z":100.0,"ID":3,"Active":true},
  "One":{"X":91.6,"Y":0.0,"Z":91.6,"ID":4,"Active":true},
  "Two":{"X":108.4,"Y":0.0,"Z":91.6,"ID":5,"Active":true},
  "Three":{"X":108.4,"Y":0.0,"Z":108.4,"ID":6,"Active":true},
  "Four":{"X":91.6,"Y":0.0,"Z":108.4,"ID":7,"Active":true}
}
```

</details>

## Timeline
![](https://preview.redd.it/ftr19z698rm91.png?width=1889&format=png&auto=webp&s=b5bbf4e5c09a28de232f19f190b4d49592eed7a1)
*(Credit: [u/ExiaKuromonji](https://www.reddit.com/r/ffxiv/comments/x9kttl/p8s_part_1_timeline/))*

## L-Stomps

"L-Stomps" refers to the following Tweet:

<blockquote class="twitter-tweet"><p lang="ja" dir="ltr">4層前半のフェイタルストンプ(ピョンピョンするやつ)近接ずっと殴れるやり方<br>(うちの学者さん考案)<br>これめっちゃいい <a href="https://t.co/wQWMBX5olX">pic.twitter.com/wQWMBX5olX</a></p>&mdash; あおいさまさま (@aoisamasama23) <a href="https://twitter.com/aoisamasama23/status/1565394643763597312?ref_src=twsrc%5Etfw">September 1, 2022</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

This is a way to resolve the Earth AoEs and the "Stomp Dead" mechanic in the first "beast" mode.

Note that the video in the Tweet uses the `A` and `2` markers to resolve the mechanic, while the macro uses `1` and `A` instead.

![](images/stomp_dead.jpg)
*(Credit: [Berga Thompson](https://jp.finalfantasyxiv.com/lodestone/character/17170591/blog/5094725/))*

## Illusory Creation

In the event the boss uses Nest of Flamevipers when the clones are 2x Dragons, the spread positions are as follows:

![](images/illusory_creation_dragon_spread.jpg)
*(Credit: [Berga Thompson](https://jp.finalfantasyxiv.com/lodestone/character/17170591/blog/5094725/))*

## Fourfold Fires

Here is how to handle the stacks/spreads in Fourfold Fires.

<table>
  <tr>
    <td><img src="images/fourfold_fires_sides_spreads.jpg"></td>
    <td><img src="images/fourfold_fires_sides_stacks.jpg"></td>
  </tr>
  <tr>
    <td><img src="images/fourfold_fires_corners_spreads.jpg"></td>
    <td><img src="images/fourfold_fires_corners_stacks.jpg"></td>
  </tr>
</table>

*(Credit: [Berga Thompson](https://jp.finalfantasyxiv.com/lodestone/character/17170591/blog/5094725/))*

## Into the Shadows #2 (Gorgon 2)

There are two strats going around for Gorgon 2 (蛇2回目 in Japanese).

### Colour-coordinated

This is the strat mostly preferred by Japanese parties.

<table>
  <tr>
    <td><p>Each T/H + DPS pair takes turns petrifying the Gorgon in their quadrant (demarcated by the coloured markers).</p><p>The player that is <em>not</em> petrifying the Gorgon places their poison puddle out of the way.</p></td>
    <td><img src="images/coloured_gorgons_1.jpg"></td>
    <td><img src="images/coloured_gorgons_2.jpg"></td>
  </tr>
</table>

### Spriggan Gorgons (fixed positions)

This is the strat done by EN parties. *Some* Japanese parties also do this strat, but they call it "Fixed Snakes 2" instead (蛇2回目固定). 

The advantage of Spriggan Gorgons is that player positions are all fixed for the first part of the mechanic.

<table>
  <tr>
    <td><p>All players are at fixed positions, regardless of where the snakes spawn.</p><p>Players should stand <b>2/3rds of the way in their tile</b> (towards the center of the arena) to not hit the other player, or the snakes with their poison puddle.</p><p>Petrify the closest snake to you when it's your turn.</p></td>
    <td><img src="images/spriggan_gorgons.jpg"></td>
  </tr>
</table>

**Clips:**
  - [Snakes at cardinals](https://www.twitch.tv/doanstv/clip/InexpensiveColdbloodedPterodactylRlyTho--3RDXuxtRjxtv1TZ)
  - [Snakes at intercardinals](https://clips.twitch.tv/SarcasticPoliteOpossumBloodTrail-1QkX3UFKiHVvAeti)

### 4:4 stacks

A clone of the boss will appear at the edge of the arena **when the second set of poison puddles go off**. The clone will destroy two of the petrified Gorgons, leaving two behind for players to resolve the last mechanic of the phase.

![](images/gorgon_2.jpg)
*(Credit: [Berga Thompson](https://jp.finalfantasyxiv.com/lodestone/character/17170591/blog/5094725/))*