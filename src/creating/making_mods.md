---
title: Making Mods
---

Many mods are created differently, so on this page you will find links to articles and guides for how to make mods of each type.

## Custom Objects

| Tutorial                                                                                                                            | Notes                                                                                                                                      |
|-------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------|
| [Devyn's Custom Weapon video tutorial playlist](https://www.youtube.com/watch?v=BScDQiGCRAM)                                        | This guide can be adapted for nearly *any* custom object and is highly recommended, albeit showing its age. Watch it before anything else. |
| [gamernayr's Grenade tutorial](implementing/grenades.md)                                                                            | The basics on making grenades. Having some previous Unity knowledge is highly recommended.                                                 |
| [Sora101TD's Unity Modmaking Tutorials](https://www.youtube.com/playlist?list=PLuiLsQZSfmynRE4qXHpeeTmwrIYSgduON)                   | Ten videos, start to finish, walking through how a custom gun is made.                                                                     |
| [ShermanJumbo's Custom Ammo Tutorial](https://youtu.be/zQ0ICkXKkr4)                                                                 | An exhaustive, modern guide on anything custom ammo.                                                                                       |
| [Local's Modular Weapon Tutorial](https://docs.google.com/document/d/1anDYvEmJk-LP4n0Gzb69jXU_Chd9uTVVNgilN-JMGik/edit?usp=sharing) | In-depth guide on making Modular weapons using CityRobo's framework.                                                                       |

## Custom Code

| Tutorial                                                                                                   | Notes                                                                                   |
|------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|
| [An introduction to scripting](scripting/intro.md)                                                         | Introductory series to setting up and creating code plugins for H3VR.                   |
| [Unity 5.6 Documentation](https://docs.unity3d.com/560/Documentation/Manual/index.html)                    | As all BepInEx plugins are just MonoBehaviours, all of the Unity documentation applies. |
| [BepInEx - Writing A Basic Plugin](https://docs.bepinex.dev/articles/dev_guide/plugin_tutorial/index.html) | BepInEx is the mod loader used for all H3VR mods.                                       |
| [Harmony2.0 - Introduction](https://harmony.pardeike.net/articles/intro.html)                              | Harmony is a patching framework used to hook and modify existing code in-game.          |

## Custom Maps

| Tutorial                                                                                                                                      | Notes                                                                                       |
|-----------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| (Recommended) [Atlas getting started guide](mapping/atlas/getting_started/1_requirements.md)                                                  | Simple guide for getting started with Atlas, the next generation of mapping tools for H3VR. |
| [Local's Mapping Guide](https://youtu.be/ATjTg0oejkg)                                                                                         | Short video guide on making maps with Atlas.                                                |
| [NunSuperior's Map Modding Tips](https://www.youtube.com/watch?v=zaIOFqZUVmI)                                                                 | NunSuperior's video is a very in-depth guide into almost every facet of making a map.       |
| [NunSuperior's Modded Map Performance Tips](https://docs.google.com/document/d/1rMcIcLBcJBFqosD6wBnVdqipfZH8vOnf_vgNLhwZ7yQ/edit?usp=sharing) | A short but useful document to increase performance in maps.                                |

## Custom Skins/Sounds

| Tutorial                                                                                   | Notes                                                                                                                                         |
|--------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| [Sora101TD's Skin Making tutorial](asset_replacement/skin_making_basics/basics_1_tools.md) | This guide is useful for making sound replacements to, or changing the assets of any other object in H3VR such as the textures for clay pots. |
| [Sora101TD's Custom TNH Hold Music tutorial](asset_replacement/tnh_music/hold_music.md)    | The best (only) take and hold music tutorial.                                                                                                 |

## Custom Characters

| Tutorial                                                                                                                                        | Notes                                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------------------|
| [Devyndamonster's Making A Custom Character tutorial](https://github.com/devyndamonster/TakeAndHoldTweaker/wiki/Making-A-Custom-Character)      | The original tutorial for making custom characters. Recommended as a starting point, covers most subjects.                                |
| [SirPotato's Custom Character Creation Guide](https://docs.google.com/document/d/1YE7iWOQGHevYE0V-CzMEu3LHfb0ejbmRV4uZz7Id-OI/edit?usp=sharing) | A newer, complete tutorial for that guides you through the entire process for creating a custom character and publishing to Thunderstore. |

## Custom PlayerBodies

| Tutorial                                                                                                                            | Notes                                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [Lunaire's PlayerBodies Tutorial](https://docs.google.com/document/d/1687-t-IiU6UWRv4FLVbj3EOJlaaTOiLWHnRDJ046Rwc/edit?usp=sharing) | Guide on how to implement PlayerBodies (Avatars, simply put) using CityRobo's framework.                                  |
| [Sora101TD's PlayerBodies Tutorial](https://discord.com/channels/685655713845870602/877599134767530004/1323012765597696071)         | Video guide on implementing PlayerBodies using JerryAr's template. Currently only available on the H3VR Homebrew discord. |

## Miscellaneous Legacy Mods
These articles are considered legacy as they refer to processes which are no longer current.

| Tutorial                                                                                                                                 | Notes                                                                                                         |
|------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| [gamernayr's packing Deli mods](delimods.md)                                                                                             | How to properly pack mods for the Deli file structure.                                                        |
| [Devyndamonster's Otherloader on-demand loading](https://github.com/devyndamonster/OtherLoader/wiki/Building-Mods-For-On-Demand-Loading) | The guide shows you how to use on-demand loading for the new version of otherloader. Not required.            |
| [Ash's Mason quick-start guide](https://h3vr-modding.github.io/Mason/getting_started/index.html)                                         | The basics on how to package a mod for Stratum/Mason.                                                         |
| [gamernayr's Making Modpacks](thunderstore/modpacks.md)                                                                                  | Got a list a mods you would like to share with the community? Take a look at this guide for making a modpack. |
| [Stratum GUIDs And Loaders](stratumdeps.md)                                                                                              | A list of Stratum loaders and their respective GUIDs.                                                         |
| [Packaging Mods For Thunderstore](thunderstore/uploading.md)                                                                             | A step-by-step tutorial on how to package your mod for Thunderstore.                                          |
| [Wurstmod - Setting Up Your Environment](https://github.com/WurstModders/WurstMod/wiki/Setting-up-your-environment)                      | A basic guide from Wurstmod on setting up your environment to make and export H3VR maps.                      |

## Deprecated
These articles have been replaced completely by more relevant ones and are here for legacy reasons.

| Tutorial                                                                                                                             | Notes                                                                                                                                                                                             |
|--------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [gamernayr's Custom Ammo tutorial](https://docs.google.com/document/d/1bF66Tijdf5mwTXuIPWmnszSNMJ8u7Wxza9_PshheB2A/edit?usp=sharing) | (Replaced by ShermanJumbo's video guide) Follow along to make custom ammo, no assets required.                                                                                                    |
| [gamernayr's modular weapon tutorial](implementing/modul/creation.md)                                                                | (Replaced by Local's written guide) This tutorial goes over converting weapons into modular ones, basing the structure off of previously created modul-series mods to ensure cross compatibility. |
| [gamernayr's pre-attached attachments tutorial](implementing/pre-attached_attachments.md)                                            | (Replaced by CityRobo's OpenScripts2) Integrated attachments and other defaulting mods can be used after reading this tutorial.                                                                   |
