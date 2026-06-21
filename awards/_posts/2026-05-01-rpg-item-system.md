---
layout: post
title:  "Rpg Item System"
summary: "Tools Programmer"
date:   2026-05-1
preview: /assets/awards/RpgItemSystem/SpringShowAward.jpg
---

<style>
div.scroll-container 
{
  background-color: #333;
  overflow: scroll;
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

* A highly modular item and attributes system to streamline workflows for RPG developers
* Winner of the <a href="https://2026springshow.academyart.edu/student/thomas-jensen/">Academy of Art University 2026 Spring Show</a> programming category

<h2>Demonstrates:</h2>

* Familiarity with and understanding of Unreal Slate, GAS, and Plugins
* Tools programming and architecture for game-agnostic systems
* Data-driven design allowing designers to customize the system to their needs
* Test-driven design using unit tests to prove the system works
* Project management, task organization, and completing milestones on a deadline
* Capability to write, follow, and update technical documentation for systems (<a href="https://docs.google.com/document/d/1wGrnzsM-1utKn-5epSmPEgBop_MC8GqGWC5BpNtbvB8/edit?usp=sharing" target="blank">view here</a>)

<h3>Features:</h3>
* Built as a plug-and-play plugin that can easily be added to existing games
* Does not require usage of a provided Unreal class (Character, Controller, Game Mode, etc)
* Includes optional example content for in-game components and widgets
* Includes custom editor windows to add/change game data:
  * <b>Item Editor</b>: Create your own items and edit existing items
  * <b>Attribute Editor</b>: Generate code for Unreal GAS attribute sets
  * <b>Affix Editor</b>: Customize how attributes are added to items
  * <b>Item Set Editor</b>: Activate bonus affixes when specific combinations of items are equipped

<div class="dont-print">
Here are some examples of items I created
<div class="dont-print">
  <body>
    <div class="scroll-container">
      <img src="/assets/awards/RpgItemSystem/BroadSword.png" alt="normal_item" width="292" height="207">
      <img src="/assets/awards/RpgItemSystem/FlamingBroadSword.png" alt="magic item" width="292" height="242">
      <img src="/assets/awards/RpgItemSystem/UniqueItem.png" alt="unique item" width="291" height="336">
      <img src="/assets/awards/RpgItemSystem/ItemSet.png" alt="set item" width="310" height="500">
    </div>
  </body>
</div>
These are the custom editor windows used to input data for the system to use
<div class="scroll-container">
  <img src="/assets/awards/RpgItemSystem/ItemEditorShort.png" alt="base item editor" width="550" height="500">
  <img src="/assets/awards/RpgItemSystem/UniqueItemEditorShort.png" alt="named item editor" width="700" height="400">
  <img src="/assets/awards/RpgItemSystem/AttributeEditorShort.png" alt="attribute editor" width="1040" height="450s">
  <img src="/assets/awards/RpgItemSystem/AffixEditorShort.png" alt="affix editor" width="650" height="500">
  <img src="/assets/awards/RpgItemSystem/ItemSetEditorFull.png" alt="item set editor" width="1456" height="500">
</div>

This is the poster I created that was displayed at the Spring Show
<img src="/assets/awards/RpgItemSystem/SpringShowPoster.png" alt="poster-failed-to-display" width="800" height="1200">
<br>
This is the video I created that was displayed alongside the poster
<video width="760" height="425" controls>
  <source src="/assets/awards/RpgItemSystem/SpringShowVideo.mp4" type="video/mp4">
</video>
</div>

<h3>Weighted Randoms:</h3>
- This project heavily utilizes weighted randoms, which allow you to modify the chance that each element has of occurring for a more specific distribution
- For example, given the values 5, 10, and 15, if higher values are meant to be more rare:
  - 5 is given a weight of 1 and has the highest chance of occurring
  - 10 is given a weight of 0.5 and has the next highest chance of occurring
  - 15 is given a weight of 0.25 and has the lowest chance of occurring

<div class="dont-print">
    <p>
        <a href="javascript:window.print();">Printer Friendly</a>
    </p>
</div>