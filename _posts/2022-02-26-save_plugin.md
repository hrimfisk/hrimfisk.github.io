--
layout: post
title:  "Expanded Save Game Library"
summary: "Programmer"
date:   2022-02-26
preview: /assets/save_game_plugin_preview.png
---

![Picture 1](/assets/save_game_plugin.png)

I created a code plugin to streamline the saving and loading process in Unreal Engine 4 & 5:
* Nodes design for simplicity with less complexity in each node, giving devs more power
* SaveGameEvents interface for Pre-Save, Pre-Load, Post-Save, Post-Load, and New Save Created
* Project Settings entry allows you to customize how the plugin works, such as single or multi file saving
* 80 blueprint nodes built entirely in C++
