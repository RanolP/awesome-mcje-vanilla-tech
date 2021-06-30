# Awesome MCJE Vanilla Tech [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> Curated List for Minecraft: Java Edition Vanilla Technique for Creating Great Stuff

## Contents

- [Basic Techniques](#basic-techniques)
- [Custom Items](#custom-items)
- [Custom Blocks](#custom-blocks)
- [Custom Entities](#custom-entities)
- [Custom UI](#custom-ui)
- [Custom Recipe](#custom-recipe)
- [Others](#others)

## Basic Techniques

- [AmberWat/NegativeSpaceFont](https://github.com/AmberWat/NegativeSpaceFont) - A hacky font for creating overlapped characters.
- [Minecraft Vanilla Shaders Guide](https://docs.google.com/document/d/15TOAOVLgSNEoHGzpNlkez5cryH3hFF3awXL5Py81EMk/) by SirBenet - A great guide for modifying the rendering pipeline of Minecraft: Java Edition with shader.

## Custom Items

### Armor

- [Custom Armor - In Vanilla Minecraft! (ft. AncientKingg)](https://youtu.be/Ape1acitJCc) by VelVoxel Raptor - Creating not only the armor item but also the armor texture by modifying shader.
- Simulating Player with Armor Stand

### Others

- [Dynamic Lore with /item in Minecraft](https://youtu.be/ffQsQQ7sJzw) by Cloud Wolf - Using score or entity name on the lore to create a dynamic lore without changing the item entirely.

## Adding Blocks

- [Custom Blocks in Minecraft](https://youtu.be/ENK0b_2yT1c) by Cloud Wolf - A comprehensive guide and examples with comparison between the one he picked, using item frame with transparent blocks, and the other methods, using armor stand(using more data than more stand), double slab with waterlogged (when it breaks, the water would be exposed), note blocks(right click would change the model, but may be good for plugins) and spawner with spawning armor stand(it has a chance to misalign the entity).

## Adding Entities

## Custom UI

### Via Font

- [Make Custom UI Bars in Minecraft](https://youtu.be/EL2X6ppZSCQ) by Cloud Wolf - A guide and example for creating UI with custom character with Action Bars.

### Via Shader

- [Flipping Gravity - In Minecraft!](https://youtu.be/L7fdljqk2jA) by VelVoxel Raptor - Creating a 90 degree flipped view by spectating or glowing entity tricks.
- [Vanilla Shader HUD/Overlay in Minecraft](https://youtu.be/Lz5eS2_BTJ4) by Cloud Wolf - A tutorial for creating UI with shader and Proof-of-Concept for dynamically changing shader UI (after 13:20), it may used the transparency shader that work when see color on a specific position(maybe center) with entity (not sure).

### Via Item

- [Thirst Bar In Vanilla Minecraft 1.10](https://youtu.be/mpoWfQ_kAxU) by VelVoxel Raptor - Creating a thirst bar by placing custom item on 9th slot of hotbar.

## Custom Recipe

- [1.13 Custom NBT Crafting Workaround](https://youtu.be/gwCwZ5ZDnvo) by VelVoxel Raptor - Adding the recipe for Spawn Eggs to make the item not acquistable by survival play and replacing the item when use to attaching NBTs to the item.

## Others

- [Fastest Right Click Detection in Minecraft](https://youtu.be/JjaFlK4L8QQ) - Using Eye of Ender to detect right click faster than Carrot of a Stick
