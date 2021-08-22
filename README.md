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

- [Custom Blocks in Minecraft](https://youtu.be/ENK0b_2yT1c) - A comprehensive guide and examples with comparison between the one he picked, using item frame with transparent blocks, and the other methods, using armor stand(consuming more data than more stand), double slab with waterlogged (when it breaks, the water would be exposed), note blocks(right click would change the model, but may be good for plugins) and spawner with spawning armor stand(it has a chance to misalign the entity).
- [Easily Create CUSTOM BLOCKS! || Minecraft Data Pack Tutorial 1.16](https://youtu.be/LUx9FqJpxQk) - Same as above one. But with more explanation about the technique.

## Custom Entities

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

This section is stub.

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

## References

<!--lint ignore double-link-->
<sup>[🔝 Back to Top](#contents)</sup>

- [Minecraft Commands Questions](https://github.com/mcfaq) - Holds a few questions about Minecraft commands.
- [A Question On Commands](https://aqoc.github.io/) - A collection of common questions related to commands, datapacks, and mapmaking in general.
- [skylinerw/guides](https://github.com/skylinerw/guides) - A set of guides about Minecraft commands.
- [Arcensoth/mcdata](https://github.com/Arcensoth/mcdata) - Version-controlled history of Minecraft's generated data.

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
- [bradleyq/light_painter](https://github.com/bradleyq/light_painter) -  Screen space point lights using MC's exposed transparency shaders.
