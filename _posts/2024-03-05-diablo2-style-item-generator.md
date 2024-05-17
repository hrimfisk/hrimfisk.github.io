---
layout: post
title:  "Diablo 2 Style Item Generator"
summary: "Programmer"
date:   2024-03-05
preview: /assets/d2_item_generator_logo.png
---
<!--![Picture 1](/assets/project_rogue.png)-->



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

This project was accepted into the AAU 2024 Spring Show and the image below is my poster<br>
- If you are on a mobile device, this page is best viewed in landscape mode<br>
- If you are having trouble viewing any images, open them in a new tab<br>
- The item tooltips in the poster are also in a list of scrollable screenshots below
<div class="dont-print">
  <img src="/assets/springShowPoster.png" alt="closePalette" width="800" height="1200">
  This is the video I created for the presentation
<iframe width="760" height="425" id="d2project" src="https://www.youtube.com/embed/G4J9fVMO-6c?si=ryjLk9EauMmLR92t" title="Presentation Video" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
Here are some screenshots
<div class="dont-print">
  <body>
    <div class="scroll-container">
      <img src="/assets/d2_item_editor.png" alt="item_editor" width="800" height="400">
      <img src="/assets/d2_affixes_editor.png" alt="affixes_editor" width="400" height="400">
      <img src="/assets/normalItemTooltip.png" alt="normal_item" width="600" height="200">
      <img src="/assets/superiorItemTooltip.png" alt="superior_item" width="600" height="280">
      <img src="/assets/magicItemTooltip.png" alt="magic_item" width="600" height="280">
      <img src="/assets/rareItemTooltip.png" alt="rare_item" width="600" height="400">
      <img src="/assets/uniqueItemTooltip.png" alt="unique_item" width="550" height="400">
      <img src="/assets/setItemTooltip.png" alt="set_item" width="400" height="400">
      <img src="/assets/setArmorTooltip.png" alt="set_armor" width="400" height="400">
      <img src="/assets/rareAmuletTooltip1.png" alt="rare_amulet1" width="360" height="280">
      <img src="/assets/rareAmuletTooltip2.png" alt="rare_amulet2" width="400" height="200">
      <img src="/assets/rareBeltTooltip.png" alt="rare_belt" width="400" height="400">
      <img src="/assets/uniqueRingTooltip.png" alt="unique_ring" width="400" height="280">
    </div>
  </body>
</div>

<h3>Weighted Randoms:</h3>
- This project heavily utilizes weighted randoms throughout the project
- Weighted randoms allow you to modify the chance that each element has of occurring for a more specific distribution
- For most systems, each subsequent element has a 50% lower chance than the previous element
  - For example:
    - 3 is given a weight of 1 and has the highest chance of occurring
    - 2 is given a weight of 0.5 and has the next highest chance of occurring
    - 1 is given a weight of 0.25 and has the lowest chance of occurring

<h3>Items:</h3>
- Each item has a chance to become a random quality based on what possibilities that base item has. 
- Some items have additional data to become a Unique or Set item
* Superior Items have a 50/50 chance for one or two affixes:
    - Weapons:
      - First Affix: Enhanced Damage
      - Second Affix: 50% chance for Attack Rating or Enhanced Durability

    - Armor:
      - First Affix: Enhanced Defense
      - Second Affix: Enhanced Durability

* Magic Items have a 50/50 chance for one or both affixes:
    - First Affix: Only a Prefix
    - Second Affix: Only a Suffix

* Rare Items have:
    - Random amount of affixes between 2 and 6
    - Each affix has 50% chance to be a prefix or suffix
    - No more than 3 prefix or suffixes

* Unique Items have:
  - Predetermined list of affixes
  - Each affix has a set value or randomizes within a range

* Set Items have:
  - Affixes like Unique items
  - Additional affixes from the set piece for number of set pieces equipped
  - Additional affixes from the item set for number of set pieces equipped

<h3>Affixes:</h3>
Affixes are broken down like so: Affix Entries contain Affix Packages, which contain Affix Ranges
* Each Affix Entry contains
  - Primary Affix
  - Secondary Affix
  - List of Affix Packages
* Each Affix Package contains
  - Level Requirement of the package
  - Weight of the package
  - Affix Range of values for the primary and possible secondary affix
  - List of base items it can appear on (e.g. belt, bow, armor, or weapon)
<h4>Choosing Affixes for an Item:</h4>
* Only 1 Affix Package per Affix Entry can be chosen when creating an item
* The level requirement of the Affix Package must be less than or equal to the item level to be chosen
<h4>Primary and Secondary Affixes:</h4>
* Affix Packages with a range are maintained as primary and secondary:
  - Minimum Damage and Maximum Damage
  - Fire Damage Minimum and Fire Damage Maximum
* Affix packages with different primary and secondary are separated:
  - Attack Rating vs. Demons and Damage vs. Demons
  - Light Radius and Attack Rating
* Affix packages with no secondary are added as-is
<h4>Adding Affixes to the Item:</h4>
* Affix packages that are chosen to be added to the item are added to existing affixes of the same affix type before being added as new affixes
* Once an item has been given its affixes, those affixes are sorted to be displayed properly
* Affix architecture is set up to allow and number of item types, not just prefixes or suffixes

<h3>Data-Driven:</h3>
* A major focus of this project was converting Items and Affixes to be entirely data-driven
* This allowed for the data to be easily editable, but also necessitated creating custom editor windows
* Data-driven elements:
  - Item list containing all data for all items
  - Affix list containing all data for all affixes
  - Item type map - detects item types and subtypes:
    - A Throwing Axe is a Thrown Weapon, but is also considered a Ranged Weapon and a Weapon
    - A Belt is its own type, but is also considered Armor
  - First and second names generated for rare items:
    - Fiend Branch
    - Cruel Cry
    - Wraith Band

<div class="dont-print">
    <p>
        <a href="javascript:window.print();">Printer Friendly</a>
    </p>
</div>