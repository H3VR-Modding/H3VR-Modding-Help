---
title: Mod Formats
uid: formats
---

Mods are packaged in a few different ways, partially due to what they rely on. However, **all mods**
require [BepInEx](https://h3vr.thunderstore.io/package/BepInEx/BepInExPack_H3VR/).

### Currently used formats:

| Name                         | Extension | Description                                                                                                                                                                         |
|------------------------------|:---------:|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| R2ModMan Package             |  `.zip`   | R2ModMan packages encompass all mods that can be used within R2ModMan. They may contain the formats below as well, but aren't required to.                                          |
| Thunderstore Package         |  `.zip`   | Thunderstore packages are a subset of R2ModMan packages that contain additional metadata. All mods found on [Thunderstore](https://h3vr.thunderstore.io) are Thunderstore packages. |
| Take & Hold Background Music |  `.bank`  | TnH Music requires [Potatoes' TNH BGM Loader](https://h3vr.thunderstore.io/package/Potatoes/Potatoes_TNH_BGM_Loader/).                                                              |
| BepInEx Plugin               |  `.dll`   | BepInEx plugins have no additional requirements.                                                                                                                                    |

### Legacy formats:

| Name           |       Extension        | Description                                                                                                                                                                                                                                                                                                        |
|----------------|:----------------------:|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Deli Mod       |        `.deli`         | Deli mods require [Deli 0.4.1](https://h3vr.thunderstore.io/package/DeliCollective/Deli/), but they may also rely on other mods. For instance, Deli mods that contain custom items or ammo also require [OtherLoader](https://h3vr.thunderstore.io/package/devyndamonster/OtherLoader/).                           |
| Sideloader Mod | `.h3mod`</br>`.hotmod` | Sideloader mods require [Sideloader](https://h3vr.thunderstore.io/package/denikson/H3VR_Sideloader/), which in turn requires [XUnity.ResourceRedirector](https://h3vr.thunderstore.io/package/bbepis/XUnity_ResourceRedirector/). These mods mostly replace assets, such as audio and textures, but can add items. |
| Asset Bundle   | `FILE` (no extension)  | Asset bundles are loaded through [OtherLoader](https://h3vr.thunderstore.io/package/devyndamonster/OtherLoader/)'s legacy loading system. These bundles are almost always a firearm, and are often accompanied by a `.manifest` file. This `.manifest` file is not needed for load the mod.                        |
