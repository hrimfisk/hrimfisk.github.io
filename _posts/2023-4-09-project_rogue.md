---
layout: post
title:  "Project Rogue"
summary: "Game and Tools Programmer"
date:   2023-04-09
preview: /assets/OtherProjects/Project_Rogue/project_rogue_preview.png
---
First-Person Rogue-lite RPG - Built in Unreal Engine 4.27

<style>
h3 
{
    font-size: 14pt;
    margin: 0;
}
h4
{
    font-size: 14pt;
    margin: 0;
}
table, tr, td
{
    border: 0px solid black;
    margin: 0;
}
tr, td
{
    padding: 0px;
}
</style>
<div class="dont-print">
<iframe width="800" height="450" src="https://www.youtube.com/embed/Ywr9jQvWZ4E" title="Project Rogue Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br>
<h4>Here is a gif of different layouts created by the Dungeon Generator. The dungeon has different parameters to control how it gets generated, such as minimum and maximum room size.</h4>
<img src="/assets/OtherProjects/Project_Rogue/dungeon_generator.gif" alt="dungeon_gif" width="800">
</div>

<!-- take screenshots of data tables to show how im using them? -->

<!--
<video width="800" height="450" controls>
    <source src="/assets/project_rogue.mp4" type="video/mp4">
    Your browser does not support this.
</video>
-->

<h3>My work:</h3>
* Created a Procedural Dungeon Generator utilizing Binary Spatial Partitioning
* Generated the contents of each dungeon room using a Grammar generator with Data Tables
* Global loot system implemented with Data Tables and weighted randoms
* Custom built UI, Stats, Inventory, Combat, and Spell systems
* Utilizes Expanded Save Game Library plugin I created for Unreal Engine
* Designed, implemented, and debugged scalable systems through prototyping and iterative development
  
<h3>Gameplay loop:</h3>
* The class you choose decides your starting equipment, then you decide how your character progresses for the rest of the game.
* Kill monsters for items and experience: leveling up gives you stat points, allowing you to use better items and learn stronger spells. Magic items increase your stats.
* Explore the endless dungeon: find and kill the dungeon boss for the key to the next level, and see how far you can go. There is no limit to the number of dungeon levels.

<h4>Design Pillars:</h4>
* Retro - The feel of games like Might & Magic IV and Legend of Grimrock
* Bring the Fantasy to Life
* Keep it Simple
* Stat-based progression

<h4>Inspirations:</h4>

<ul>
<table style="width: 100%">
  <tr>
    <td style="width: 50%">
      <li>Might & Magic IV: Clouds of Xeen</li>
    </td>
    <td>
      <li>Diablo 2</li>
    </td>
  </tr>
  <tr>
    <td>
      <li>Dark Souls series</li>
    </td>
    <td>
      <li>Legend of Grimrock</li>
    </td>
  </tr>
  <tr>
    <td>
      <li>World of Warcraft</li>
    </td>
    <td>
      <li>Skyrim</li>
    </td>
  </tr>
  <tr>
    <td>
      <li>Borderlands</li>
    </td>
  </tr>
</table>
</ul>

<div class="dont-print">
    <p>
        <a href="https://store.steampowered.com/app/2519470/Project_Rogue/">Steam Link</a>
        <a href="javascript:window.print();" style="float: right">Printer Friendly</a>
    </p>
</div>