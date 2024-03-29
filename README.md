# Awesome MCJE Vanilla Tech [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![License: CC0](https://img.shields.io/badge/License-CC0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> Curated List for Minecraft: Java Edition Vanilla Technique for Creating Great Stuff

You may also want to see [lolgeny/awesome-mcc](https://github.com/lolgeny/awesome-mcc).

## Contents

- [Basic Techniques](#basic-techniques)
- [Custom Items](#custom-items)
- [Custom Blocks](#custom-blocks)
- [Custom Entities](#custom-entities)
- [Custom UI](#custom-ui)
- [Custom Recipe](#custom-recipe)
- [Softwares](#softwares)
- [Utilities](#utilities)
- [Guides](#guides)
- [Other Techniques](#other-techniques)
- [Communities](#communities)
- [Experiments](#experiments)
- [Works](#works)

## Basic Techniques

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [AmberWat/NegativeSpaceFont](https://github.com/AmberWat/NegativeSpaceFont) - A hacky font for creating overlapped characters.
- [Minecraft Vanilla Shaders Guide](https://docs.google.com/document/d/15TOAOVLgSNEoHGzpNlkez5cryH3hFF3awXL5Py81EMk/) - A great guide for modifying the rendering pipeline of Minecraft: Java Edition with shader.
- [Entity Shaders in Minecraft [1.15+] [Datapack]](https://youtu.be/r29Rj01t_Cs) - Applying shader of an entity using bug, be careful when using this and may be removed in future version.
- [Toggleable Minecraft shaders](https://pastebin.com/Z2Q47AfT) - Great guide for shader selection technique.
- [5uso/Mod-Warnings](https://github.com/5uso/Mod-Warnings) - An weird technique to detect mods.

## Custom Items

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

### Armor

- [Ancientkingg/fancyPants](https://github.com/Ancientkingg/fancyPants) - Creating not only the armor item but also the armor texture by modifying shader.
- Simulating Player with Armor Stand

### Others

- [Dynamic Lore with /item in Minecraft](https://youtu.be/ffQsQQ7sJzw) - Using score or entity name on the lore to create a dynamic lore without changing the item entirely.

## Custom Blocks

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [Custom Blocks in Minecraft](https://youtu.be/ENK0b_2yT1c) - A comprehensive guide and examples with comparison between the one he picked, using item frame with transparent blocks, and the other methods, using armor stand(consuming more data than item frame), double slab with waterlogged (when it breaks, the water would be exposed), note blocks(right click would change the model, but may be good for plugins) and spawner with spawning armor stand(it has a chance to misalign the entity).
- [Easily Create CUSTOM BLOCKS! || Minecraft Data Pack Tutorial 1.16](https://youtu.be/LUx9FqJpxQk) - Same as above one. But with more explanation about the technique.

## Custom Entities

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [unnamed/hephaestus-engine](https://github.com/unnamed/hephaestus-engine) - Render, animate and interact with custom entity models in Minecraft: Java Edition servers.

## Custom UI

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

### Visual

#### Via Font

- [Make Custom UI Bars in Minecraft](https://youtu.be/EL2X6ppZSCQ) - A guide and example for creating UI with custom character on Action Bars.
- [Darken Screen Effect in Minecraft](https://youtu.be/FkLtgmW_JpU) - Using big enough character on title to create a darken screen effect.

#### Via Shader

- [Flipping Gravity - In Minecraft!](https://youtu.be/L7fdljqk2jA) - Creating a 90 degree rotated view by spectating or glowing entity tricks.
- [Vanilla Shader HUD/Overlay in Minecraft](https://youtu.be/Lz5eS2_BTJ4) - A tutorial for creating UI with shader and Proof-of-Concept for dynamically changing shader UI (after 13:20), it may used the Toggleable Minecraft shaders from Basic Technique section.
- [Removing Red Numbers From Sidebars (1.17)](https://youtu.be/dD6V0bKf-Bc) - A shader trick to remove red numbers on sidebar from the game, however it removes some red numbers on not critical places too.
- [lolgeny/item-tooltip-remover](https://github.com/lolgeny/item-tooltip-remover) - Simple shader that removes tooltips on specific items, for custom guis.

#### Via Item

- [Thirst Bar In Vanilla Minecraft 1.10](https://youtu.be/mpoWfQ_kAxU) - Creating a thirst bar by placing custom item on 9th slot of hotbar.

### Implementation

- [Chest Menu/GUI Tutorial in Minecraft](https://youtu.be/OOuRyx0Ipe4) - A full guide to create chest menu with vanilla commands.
- [Drop Item Menu/GUI Tutorial in Minecraft [1.14/15+]](https://youtu.be/mbwhc5qC47k) - A full guide to create drop item menu with vanilla commands.

## Custom Recipe

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [1.13 Custom NBT Crafting Workaround](https://youtu.be/gwCwZ5ZDnvo) - Adding the recipe for Spawn Eggs to make the item not acquistable by survival play and replacing the item when use to attaching NBTs to the item.

## Softwares

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [Blockbench](https://www.blockbench.net/) - Awesome modeling program for Minecraft.
- [mcbeet/beet](https://github.com/mcbeet/beet) - Toolchain for creating data pack and resource pack.
- [Open Note Block Studio](https://opennbs.org/) - Good tool for creating a song using note blocks.
- [OrangeUtan/vscode-mcmodel-viewer](https://github.com/OrangeUtan/vscode-mcmodel-viewer) - A model viewer for Visual Studio Code.
- [SPYGlassMC/vscode-datapack](https://github.com/SPYGlassMC/vscode-datapack) - Good extension for creating data packs on Visual Studio Code.
- [misode/vscode-nbt](https://github.com/misode/vscode-nbt) - VSCode extension to view Minecraft NBT files. For structure files, this shows a 3D block view.
- [Amulet-Team/Amulet-Map-Editor](https://github.com/Amulet-Team/Amulet-Map-Editor) -  A new Minecraft world editor and converter that supports all versions since Java 1.12 and Bedrock 1.7. Actually, it is a spiritual successor of MCEdit and its unified version.
- [MCStacker](https://mcstacker.net/) - Various command generator.
- [Minecraft Heads](https://minecraft-heads.com/) - A collection of decorative head textures.
- [Tellraw Generator for Minecraft](https://www.minecraftjson.com/) - Not only generates the tellraw but also generates the other JSON text related commands.
- [Minecraft Statue Generator 1.17+](https://raketenben.github.io/statue-generator/) - Creating a statue of a player with a lot of Armor Stands. Do not use any resource-pack at all.
- [Chunker](https://chunker.app/) - A world converter for going between Bedrock and Java.
- [tryashtar/nbt-studio](https://github.com/tryashtar/nbt-studio) - A spritual successor of NBTExplorer.

### Programming Languages compiles to MCFunction

- [Miestrode/bell](https://github.com/Miestrode/bell) - Work in progress programming language to help Minecraft data pack developers work smarter and faster.
- [Inky-developer/debris](https://github.com/Inky-developer/debris) - Debris is a powerful language & compiler which aims to make the process of creating a datapack easier and quicker.
- [EMCL Compiler](https://heledron.com/tools/emcl-compiler/) - EMCL (Extended Minecraft Command Language) is a language designed to compile to Minecraft function files. It implements data types, mathematical expressions, and high-level control flow like loops.

## Utilities

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [MC Assets](https://mcasset.cloud/) - Getting Minecraft assets without digging Minecraft files.
- [Plagiatus/MapmakingTemplate](https://github.com/Plagiatus/MapmakingTemplate) - A good template for making a great map.

## Guides

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [Minecraft Commands Questions](https://github.com/mcfaq) - Holds a few questions about Minecraft commands.
- [A Question On Commands](https://aqoc.github.io/) - A collection of common questions related to commands, datapacks, and mapmaking in general.
- [skylinerw/guides](https://github.com/skylinerw/guides) - A set of guides about Minecraft commands.
- [Arcensoth/mcdata](https://github.com/Arcensoth/mcdata) - Version-controlled history of Minecraft's generated data.
- [How not to use `execute`](https://gist.github.com/Aeldrion/419e3da12666280cbfd2dabf567dc36c) - A guide for avoiding substitutable execute commands.

## Other Techniques

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [Fastest Right Click Detection in Minecraft](https://youtu.be/JjaFlK4L8QQ) - Using Eye of Ender to detect right click faster than Carrot of a Stick.
- [Detect HEADSHOTS, Make LASER GATES - Precise Hitbox Detection || Minecraft Datapack Tutorial](https://youtu.be/kKS3sF0X4Is) - Good method to check precise hitbox collision.
- [[Concept] Simple translational dynamics with ray-casting [MC 1.10.X]](https://youtu.be/ljm0Aj3G7qo) - (just for the archive) When Minecraft doesn't have built-in ray tracing method. Achieved by using boat and showed some examples utilizing the technique.

## Communities

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [/r/MinecraftCommands](https://www.reddit.com/r/MinecraftCommands/) - Big Reddit Minecraft command community. It has a GitHub organization and Discord server.

## Experiments

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [TheEpicBlock/PolyMc](https://github.com/TheEpicBlock/PolyMc) - A Fabric mod makes the client not to require Fabric mods by converting the mods' stuff with Vanilla's one.
- [oraxen/oraxen](https://github.com/oraxen/oraxen) - Oraxen is a minecraft plugin that allows to easily use Minecraft 1.14 features in order to create new items with custom textures. It handles the resourcepack generation, upload (using Polymath), is fully open source and has an extensible API.

## Works

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [[1.14 ~ 1.14.4] DIO DataPack](https://www.planetminecraft.com/data-pack/1-14-dio-datapack/) - Aesthetic example for shader selection and animation.
- [[19w06a] Immortal Soul - Brand New Form Boss Fight Map](https://www.planetminecraft.com/project/19w06a-immortal-soul-brand-new-form-boss-fight-map/) - Great application of various techniques.
- [MapleCraft - An old version Maplestory project](https://www.planetminecraft.com/project/maplecraft-an-old-version-maplestory-project/) - How did they get here?
- [OrangeUtan/mc-wind-shader](https://github.com/OrangeUtan/mc-wind-shader) - Creating wind effect on leaves by using shader.
- [bradleyq/mc_vanilla_shaders](https://github.com/bradleyq/mc_vanilla_shaders) - Creating water reflection by using shader.
- [bradleyq/shader-toolkit](https://github.com/bradleyq/shader-toolkit) - Useful Minecraft: Java Edition 1.17 Vanilla shader examples.
- [onnowhere/Color-Blindness-Simulation-Shaders](https://github.com/onnowhere/Color-Blindness-Simulation-Shaders) - Shaders simulating 8 different color blindness types. Intended for vanilla Minecraft 1.16.2.
- [bradleyq/light_painter](https://github.com/bradleyq/light_painter) - Screen space point lights using MC's exposed transparency shaders.
- [ICY105/Mechanization](https://github.com/ICY105/Mechanization) - A Minecraft datapack aimed at recreating popular tech mods like IC2 and Thermal Expansion. 
- [eatYourHashs/florcraft](https://github.com/eatYourHashs/florcraft) - A magic datapack inspired by Thaumcraft and centered around nature magic.
- [eatYourHashs/UM](https://github.com/eatYourHashs/UM) - Undermagic, a minecraft datapack adding a massive amount of content and boss battles.
- [asdru22/Accessory-Bag](https://github.com/asdru22/Accessory-Bag) -  Adds accessories and other small features.
- [tempestsbox/ttb](https://github.com/tempestsbox/ttb) - The Tempest's Box adds countless features to the game, providing you with many new items, blocks, entities, structures, and more!
- [Gamemode 4](https://gm4.co/) - Gamemode 4 is an open-source data pack collection designed to augment the vanilla survival experience. We aim to provide well balanced, vanilla-like extensions, all whilst having minimal performance impact!
- [McTsts/mc-core-shaders](https://github.com/McTsts/mc-core-shaders) - A collection of shaders containing hide scoreboard number trick, blinking eye of one's skin with damage color customization, and more.
