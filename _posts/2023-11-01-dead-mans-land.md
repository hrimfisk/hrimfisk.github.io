---
layout: post
title:  "Dead Man's Land"
summary: "Game Programmer"
date:   2024-03-05
preview: /assets/Dead_Mans_Land/preview.png
---
<!--![Picture 1](/assets/project_rogue.png)-->

- This is a Zombie Shooter I built in Unreal Engine 5 as a Winter 2023-2024 project
- The goal with this project was building a simple game and experimenting with reusability

<style>
div.scroll-container 
{
  background-color: #333;
  overflow: auto;
  white-space: nowrap;
  padding: 10px;
}

div.scroll-container img 
{
  padding: 10px;
}
highlight 
{
    color: #2A9094;
}
</style>

<div class="dont-print">
<!--
<img src="/assets/Dead_Mans_Land/preview_full.png" alt="preview_full" width="800" height="400">
-->

<iframe width="800" height="450" src="https://www.youtube.com/embed/eA4lZjudKfM?si=wjnp7L3biUQ_x7nN" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>

<h3>Game Mechanics:</h3>
* Zombies have a chance to drop Blood Samples
* Blood Samples can be used to:
    - Open Doors
    - Clear Debris
    - Win the Game
* 2 Chests randomly spawn in each room and provide a random amount of Metal Scraps
* Metal Scraps are used to craft a random amount of Bullets
* Deposit Blood Samples into the Blood Sample Collected for a random item:
  - Metal Scraps
  - Blood Samples
  - Restore Health

In this example, I created a data table for a centralized location for all sound data, and a blueprint function library to play sounds and easily reference that data

<div class="row">
  <div class="column">
    <img src="/assets/Dead_Mans_Land/sound_data.png" alt="sound_data" width="400" height="400">
  </div>
  <div class="column">
    <img src="/assets/Dead_Mans_Land/play_sound.png" alt="play_sound" width="390" height="316">
  </div>
</div>

For the level layout, I recreated the classic Call of Duty Nazi Zombies level: Nacht Der Untoten
<div class="dont-print">
<img src="/assets/Dead_Mans_Land/birds_eye_view.png" alt="birds_eye_view" width="800" height="400">
<img src="/assets/Dead_Mans_Land/player_start.png" alt="player_start" width="800" height="400">
</div>

<div class="dont-print">
    <p>
        <a href="javascript:window.print();">Printer Friendly</a>
    </p>
</div>