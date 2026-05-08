---
layout: post
title:  "Rpg Item System"
summary: "Tools Programmer"
date:   2026-05-1
preview: /assets/awards/RpgItemSystem/SpringShowPosterPreview.png
---
<!--![Picture 1](/assets/project_rogue.png)-->



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

* I created a highly modular item and attributes system for RPG developers
* Winner of the <a href="https://2026springshow.academyart.edu/student/thomas-jensen/">Academy of Art University 2026 Spring Show</a> programming category

<h2>Demonstrates:</h2>

* Familiarity with and understanding of Unreal Slate and GAS
* Tools programming and architecture for game-agnostic systems
* Project management, task organization, and completing milestones on a deadline
* Data-driven design allows designers to make their own rules

<h2>Features:</h2>

* Item Editor: Create your own items
* Attribute Editor: Generate code for Unreal GAS attribute sets
* Affix Editor: Decide how items increase your character's attributes
* Item Set Editor: Activate bonus affixes when specific combinations of items are equipped

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
<br>
These are the custom editor windows used to input data for the system to use
<div class="scroll-container">
  <img src="/assets/awards/RpgItemSystem/ItemEditorShort.png" alt="base item editor" width="550" height="500">
  <img src="/assets/awards/RpgItemSystem/UniqueItemEditorShort.png" alt="named item editor" width="858" height="450">
  <img src="/assets/awards/RpgItemSystem/AttributeEditorShort.png" alt="attribute editor" width="1040" height="450s">
  <img src="/assets/awards/RpgItemSystem/AffixEditorShort.png" alt="affix editor" width="650" height="500">
  <img src="/assets/awards/RpgItemSystem/ItemSetEditorFull.png" alt="item set editor" width="1456" height="500">
</div>

This is the poster I created that was displayed at the spring show
<img src="/assets/awards/RpgItemSystem/springShowPoster.png" alt="poster" width="800" height="1200">

This is the video I created that was displayed next to the poster
<video width="760" height="425" controls>
  <source src="/assets/awards/RpgItemSystem/SpringShowVideo.mp4" type="video/mp4">
</video>
</div>


<h3>Weighted Randoms:</h3>
- This project heavily utilizes weighted randoms
- Weighted randoms allow you to modify the chance that each element has of occurring for a more specific distribution
- For most systems, each subsequent element has a 50% lower chance than the previous element
  - For example:
    - 3 is given a weight of 1 and has the highest chance of occurring
    - 2 is given a weight of 0.5 and has the next highest chance of occurring
    - 1 is given a weight of 0.25 and has the lowest chance of occurring

<div class="dont-print">
    <p>
        <a href="javascript:window.print();">Printer Friendly</a>
    </p>
</div>