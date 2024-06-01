---
layout: post
title:  "Save Game Library Plugin"
summary: "Tools Programmer"
date:   2024-05-05
preview: /assets/Experience/SaveGameLibraryPlugin/ExpSaveIconUEContent.png
---
I wrote a C++ plugin to streamline the saving and loading process in Unreal Engine

<!--![Picture 1](/assets/save_game_plugin.png)-->
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
  <img src="/assets/Experience/SaveGameLibraryPlugin/store_page.png" alt="nodes" width="800" height="450">
  <img src="/assets/Experience/SaveGameLibraryPlugin/review2.png" alt="nodes" width="800" height="120">
  <img src="/assets/Experience/SaveGameLibraryPlugin/review1.png" alt="nodes" width="800" height="255">
  <h3><a href="https://www.unrealengine.com/marketplace/en-US/product/expanded-save-game-library?sessionInvalidated=true">Link to Marketplace Page</a></h3>
</div>


* Blueprint function library with 80 functions accessible from any blueprint, including widgets
* Functions designed for simplicity with less complexity in each function, giving developers more control
  - Save entire arrays and structs, or store values individually
  - Easily retrieve stored data with less input
* SaveGameEvents interface for ease of use and more control of the saving and loading process
  - Event PreSave is triggered just before a game is saved
  - Event PreLoad is triggered just before a game is loaded
  - Event PostSave is triggered right after a game is saved
  - Event PostLoad is triggered right after a game is loaded
  - Event OnActorsSpawned is triggered after SpawnEachStoredAfter is called
  - Event OnNewSaveCreated is triggered when NewSaveGame is called
* Project Settings entry allows you to customize how the plugin works
* The system is fully accessible in C++ and can be extended as needed
* 55 copies sold on the Unreal Marketplace as of 05/24/2024


<div class="dont-print">
    <p>
          <a href="javascript:window.print();">
            Printer Friendly
          </a>
    </p>
</div>