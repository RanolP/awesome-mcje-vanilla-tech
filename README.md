# Awesome MCJE Vanilla Tech [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> Curated List for Minecraft: Java Edition Vanilla Technique for Creating Great Stuff

## Contents

- [Basic Techniques](#basic-techniques)
- [Custom Items](#custom-items)
- [Custom Blocks](#custom-blocks)
- [Custom Entities](#custom-entities)
- [Custom UI](#custom-ui)
- [Custom Recipe](#custom-recipe)
- [Softwares](#softwares)
- [References](#references)
- [Other Techniques](#other-techniques)
- [Works](#works)

## Basic Techniques

<sup>[🔝 Back to Top](#contents)</sup>

- [AmberWat/NegativeSpaceFont](https://github.com/AmberWat/NegativeSpaceFont) - A hacky font for creating overlapped characters.
- [Minecraft Vanilla Shaders Guide](https://docs.google.com/document/d/15TOAOVLgSNEoHGzpNlkez5cryH3hFF3awXL5Py81EMk/) by SirBenet - A great guide for modifying the rendering pipeline of Minecraft: Java Edition with shader.
- [Entity Shaders in Minecraft [1.15+] [Datapack]](https://youtu.be/r29Rj01t_Cs) by Cloud Wolf - Applying shader of an entity using bug, be careful when using this and may be removed in future version.
- [Toggleable Minecraft shaders](https://pastebin.com/Z2Q47AfT) - Great guide for shader selection technique.

## Custom Items

<sup>[🔝 Back to Top](#contents)</sup>

### Armor

- [Custom Armor - In Vanilla Minecraft! (ft. AncientKingg)](https://youtu.be/Ape1acitJCc) by VelVoxel Raptor - Creating not only the armor item but also the armor texture by modifying shader.
- Simulating Player with Armor Stand

### Others

- [Dynamic Lore with /item in Minecraft](https://youtu.be/ffQsQQ7sJzw) by Cloud Wolf - Using score or entity name on the lore to create a dynamic lore without changing the item entirely.

## Custom Blocks

<sup>[🔝 Back to Top](#contents)</sup>

- [Custom Blocks in Minecraft](https://youtu.be/ENK0b_2yT1c) by Cloud Wolf - A comprehensive guide and examples with comparison between the one he picked, using item frame with transparent blocks, and the other methods, using armor stand(using more data than more stand), double slab with waterlogged (when it breaks, the water would be exposed), note blocks(right click would change the model, but may be good for plugins) and spawner with spawning armor stand(it has a chance to misalign the entity).
- [Easily Create CUSTOM BLOCKS! || Minecraft Data Pack Tutorial 1.16](https://youtu.be/LUx9FqJpxQk) by Timber Forge - Same as Cloud Wolf's one. But with more explanation about the technique.

## Custom Entities

<sup>[🔝 Back to Top](#contents)</sup>

This section is stub.

## Custom UI

<sup>[🔝 Back to Top](#contents)</sup>

### Visual

#### Via Font

- [Make Custom UI Bars in Minecraft](https://youtu.be/EL2X6ppZSCQ) by Cloud Wolf - A guide and example for creating UI with custom character with Action Bars.
- [Darken Screen Effect in Minecraft](https://youtu.be/FkLtgmW_JpU) by Cloud Wolf - Using big enough character on title to create a darken screen effect.

#### Via Shader

- [Flipping Gravity - In Minecraft!](https://youtu.be/L7fdljqk2jA) by VelVoxel Raptor - Creating a 90 degree flipped view by spectating or glowing entity tricks.
- [Vanilla Shader HUD/Overlay in Minecraft](https://youtu.be/Lz5eS2_BTJ4) by Cloud Wolf - A tutorial for creating UI with shader and Proof-of-Concept for dynamically changing shader UI (after 13:20), it may used the transparency shader that work when see color on a specific position(maybe center) with entity (not sure).

#### Via Item

- [Thirst Bar In Vanilla Minecraft 1.10](https://youtu.be/mpoWfQ_kAxU) by VelVoxel Raptor - Creating a thirst bar by placing custom item on 9th slot of hotbar.

### Implementation

- [Chest Menu/GUI Tutorial in Minecraft](https://youtu.be/OOuRyx0Ipe4) by Cloud Wolf - A full guide to create chest menu with vanilla commands.
- [Drop Item Menu/GUI Tutorial in Minecraft [1.14/15+]](https://youtu.be/mbwhc5qC47k) by Cloud Wolf - A full guide to create drop item menu with vanilla commands.

## Custom Recipe

<sup>[🔝 Back to Top](#contents)</sup>

- [1.13 Custom NBT Crafting Workaround](https://youtu.be/gwCwZ5ZDnvo) by VelVoxel Raptor - Adding the recipe for Spawn Eggs to make the item not acquistable by survival play and replacing the item when use to attaching NBTs to the item.

## Softwares

<sup>[🔝 Back to Top](#contents)</sup>

- [Blockbench](https://www.blockbench.net/) - Awesome modeling program for Minecraft.
- [mcbeet/beet](https://github.com/mcbeet/beet) - Toolchain for creating data pack and resource pack.
- [Open Note Block Studio](https://opennbs.org/) - Good tool for creating a song using note blocks.
- [OrangeUtan/vscode-mcmodel-viewer](https://github.com/OrangeUtan/vscode-mcmodel-viewer) - A model viewer for Visual Studio Code.
- [SPYGlassMC/vscode-datapack](https://github.com/SPYGlassMC/vscode-datapack) - Good extension for creating data packs on Visual Studio Code.

## Other Techniques

<sup>[🔝 Back to Top](#contents)</sup>

- [Fastest Right Click Detection in Minecraft](https://youtu.be/JjaFlK4L8QQ) by Cloud Wolf - Using Eye of Ender to detect right click faster than Carrot of a Stick
- [Detect HEADSHOTS, Make LASER GATES - Precise Hitbox Detection || Minecraft Datapack Tutorial](https://youtu.be/kKS3sF0X4Is) by Timber Forge - Good method to check precise hitbox collision.

## References

<sup>[🔝 Back to Top](#contents)</sup>

- [Minecraft Commands Questions](https://github.com/mcfaq) - Holds a few questions about Minecraft commands.
- [A Question On Commands](https://aqoc.github.io/) - A collection of common questions related to commands, datapacks, and mapmaking in general.

## Works

<sup>[🔝 Back to Top](#contents)</sup>

- [[1.14 ~ 1.14.4] DIO DataPack](https://www.planetminecraft.com/data-pack/1-14-dio-datapack/) - Aesthetic example for shader animation.
- [[19w06a] Immortal Soul - Brand New Form Boss Fight Map](https://www.planetminecraft.com/project/19w06a-immortal-soul-brand-new-form-boss-fight-map/) - Great application of various techniques.
- [MapleCraft - An old version Maplestory project](https://www.planetminecraft.com/project/maplecraft-an-old-version-maplestory-project/) - How did they get here?
- [OrangeUtan/mc-wind-shader](https://github.com/OrangeUtan/mc-wind-shader) - Creating wind effect on leaves by using shader.
