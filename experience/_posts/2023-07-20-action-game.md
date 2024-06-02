---
layout: post
title:  "Unannounced Action Game"
summary: "Game Programmer"
date:   2024-05-27
preview: /assets/Experience/Exoforge/exoforge_preview.png
---
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
h2
{
  padding: 0px;
}
</style>

I provided freelance programming work on an unannounced project in UE4 with numerous features<br>
<h2>Demonstrates:</h2>
* Strong C++ skills and the ability to code and architect gameplay mechanics and tools
* Expertise with Unreal Engine and game development concepts
* Strong analytical abilities with creative problem-sovling skills, excelling in thinking innovatively and finding unique solutions
* Experience of networking game features and awareness of the complexities of networked gameplay (replication of state, behaviors, client/server breakdown of features and game systems)


<!--![Picture 1](/assets/save_game_plugin.png)-->

<meta name="viewport" content="width=device-width, initial-scale=1.0"> 
<div class="dont-print">
  <body>
<br>
  <img src="/assets/Experience/Exoforge/spending_credits.gif" alt="char_customize_gif" width="800">
  - I implemented a credits system that allows you to spend credits to unlock colors. It can be expanded to unlock potentially anything<br><br>
  <div class="row">
    <div class="column">
      <img src="/assets/Experience/Exoforge/character_customization_cropped.gif" alt="char_customize_gif" width="400">
    </div>
    <div class="column">
      <img src="/assets/Experience/Exoforge/vehicle_customization.gif" alt="veh_customize_gif" width="400">
    </div>
  </div>
  - I expanded the customization system to allow for different color palettes for different categories and different materials of the model<br><br>

<img src="/assets/Experience/Exoforge/crafting_requirements.gif" alt="char_customize_gif" width="800">
  - Resources: I implemented a resource system and added level requirements to craft gear. You need to harvest a resource and level up to craft gear with that resource<br>
  - I'm using a debug menu to give myself levels to demonstrate not meeting requirements, then leveling up and meeting the requirements<br><br>
      <img src="/assets/Experience/Exoforge/exoforge_inventory.png" alt="inventory" width="800" height="400">
  - I added a carrying capacity system to encumber the player when carrying too much, and a mod system to augment your character in various ways<br><br>
  </body>
</div>

<h3>My best work:</h3>
* Credits system:
  - Players convert resources into credits
  - Players spend credits to unlock customization colors, and potentially anything else
* Mod system:
  - Allow players to augment their character by equipping mods
  - Designers can easily create their own custom mods or add mod slots
* Cargo system:
  - Allows players to transfer items between worlds
  - Includes personal and public storage.
* Temperature system: 
  - Allows designers to add hot or cold areas to any world
  - Temperature zones can be overlapped, using priority to determine how they get used
  - If the player is too hot or cold, they will start losing health in increments

<h3>The rest of my work:</h3>
* Implemented:
  - Various bug fixes to existing systems from a marketplace asset pack, including merging blueprint
  - Cargo system for transferring items between worlds
  * Vehicle customization system
  - Customize the components of the chasis and wheels
  - Melee mechanic to reduce incoming damage when blocking
  - Temperature system for designers to add hot or cold areas
    - If the player is too hot or cold, they will start losing health in increments
  - Player input remapping system
  - Stats for players to keep track of their kills

* Improved:
  - Crafting systems; vehicles, weapons, armor
  - Travel system to allow players to easily move between worlds
  - Debug menu by adding features such as resetting saved spawn location
  - Health and Steam icon display over players
  - Crouch and Swim:
    - Cannot uncrouch under a surface
    - Can now mantle an object at the surface of water
  - Character customization with additional color palettes and character species options
  - Buff system to include temperature and oxygen buffs
  - Resource and mining system:
    - Mining a resources increases your level with that resource
    - Equipment you craft with a refined resource may require a specific level of that resource to use
    - Prevented raw resources from being transferred from a world to the lobby  

<div class="dont-print">
    <p>
        <a href="javascript:window.print();">Printer Friendly</a>
    </p>
</div>