---
layout: post
title:  "Save Game Library Plugin"
summary: "Programmer"
date:   2022-02-16
preview: /assets/disk.png
---
I wrote a C++ plugin to streamline the saving and loading process in Unreal Engine 4/5:<br>

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
  <body>
    <div class="scroll-container">
      <img src="/assets/save_game_plugin.png" alt="nodes" width="600" height="400">
      <img src="/assets/save_game_events.png" alt="events" width="600" height="400">
      <img src="/assets/save_game_settings.png" alt="settings" width="600" height="400">
    </div>
  </body>
</div>

* Blueprint function library with 80 functions accessible from any blueprint, including widgets
* Functions designed for simplicity with less complexity in each function, giving developers more control
* SaveGameEvents interface for ease of use and more control of the saving and loading process
* Project Settings entry allows you to customize how the plugin works
* <highlight>48 copies sold on the Unreal Marketplace as of 05/07/2023</highlight>


<div class="dont-print">
    <p>
        <a href="https://www.unrealengine.com/marketplace/en-US/product/expanded-save-game-library?sessionInvalidated=true">
          Marketplace Link
        </a>
        <span style="float: right">
          <a href="javascript:window.print();">
            Printer Friendly
          </a>
        </span>
    </p>
</div>