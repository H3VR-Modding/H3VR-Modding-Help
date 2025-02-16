---
title: Deli mods
---

> [!WARNING]
> Deli is not supported anymore. The following information is here for legacy reasons only. If you were linked here
from a seemingly updated article, [open an issue](https://github.com/H3VR-Modding/wiki/issues/new).

Deli was a popular format of packaging mods, and can be anything from maps, code mods, or guns.

All a `.deli` file is, is a `.zip` renamed.

## Recognizing what mod you have

Deli supports the following mod types:

- Custom characters (TnHTweaker)
- Maps (Wurstmod/[REDACTED])
- Guns/Items (Otherloader pre 1.0.0)

If you have a sound mod or an asset replacement, you need Sideloader.

## The Manifest

Copy this text into a file called `manifest.json`:

```json
{
  "guid": "",
  "version": "",
  "require": "0.4.1",
  "dependencies": {
  },
  "name": "",
  "description": "",
  "authors": [
  ],
  "assets": {
  }
}
```

Change the fields to match your mod:

- `"guid"`: The id of your mod. Cannot contain capitals or punctuation.
    - Example: "author.mod.name"
- `"version"`: Version of the mod.
    - Example: "1.0.0"
- `"require"`: Which version of Deli this mod required. You should use "0.4.2".
- `"depedencies"`: Which mods this mod depends on. Leave this blank since Thunderstore now takes care of this for us.
- `"name"`: The name of the mod.
    - Example: "CoolMod"
- `"description"`: Unused, don't change.
- `"authors"`: A list of people who made the mod. Also unused, don't change.
- `"assets"`: The list of files your mod needs to load.

The following sections are mod type specific, and tell you what you need to place in your `"assets"`

## Custom Characters

Here is the file structure of the `.deli` file:

```text
mod.deli/
    manifest.json
    character/
        character.json
        sosig_...
        vault_...
```

Your `character.json` file should be inside a folder, named anything you want. In this example I used the `character`
name. Your sosigs should have the "sosig_" prefix, and your vault files should have the "vault_" prefix.

This should make the following list for you to copy into your `"asssets"` list:

```json
        "setup": {
"character/": "h3vr.tnhtweaker.deli:character",
"character/sosig_*.json": "h3vr.tnhtweaker.deli:sosig",
"character/*vault*.json": "h3vr.tnhtweaker.deli:vault_file"
}
```

For an example of a completed manifest:

```json
{
  "guid": "h3vr.name.mod",
  "version": "1.0.0",
  "require": "0.4.2",
  "dependencies": {
  },
  "name": "CoolMod",
  "description": "",
  "authors": [
  ],
  "assets": {
    "setup": {
      "character/": "h3vr.tnhtweaker.deli:character",
      "character/sosig_*.json": "h3vr.tnhtweaker.deli:sosig",
      "character/*vault*.json": "h3vr.tnhtweaker.deli:vault_file"
    }
  }
}
```

## Maps

This section is still in development, come back later.

## Guns/Items

Here is the file structure of the `.deli` file:

```text
mod.deli/
    manifest.json
    item
```

Your `item` is the assetbundle created through Unity. You do not need to include its `.manifest` file, but you can.
Do **NOT** reference this file inside the manifest.

This should make the following list for you to copy into your `"asssets"` list:

```json
        "runtime": {
"item": "h3vr.otherloader.deli:item"
}
```

Making the example look like:

```json
{
  "guid": "h3vr.name.mod",
  "version": "1.0.0",
  "require": "0.4.2",
  "dependencies": {
  },
  "name": "CoolMod",
  "description": "",
  "authors": [
  ],
  "assets": {
    "runtime": {
      "item": "h3vr.otherloader.deli:item"
    }
  }
}
```
