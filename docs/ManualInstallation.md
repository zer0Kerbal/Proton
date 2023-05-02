---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
Протон (Proton)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Протон (Proton)

[Home](./index.md)

The Soviet Space Station MIR for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `BobCat` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/BobCat/SovietPack/Proton`
* Extract the package's `BobCat/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/BobCat` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/BobCat/SovietPack/Proton`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/BobCat/SovietPack/Proton`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/BobCat/SovietPack/Proton`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [BobCat]
      + [SovietPack]
        + [Proton]
          + [Assets]
            ...
          + [Compatibility]
            ...
          + [Config]
            ...
          + [Contracts]
            ...
          + [Localization]
            ...
          + [Parts]
            ...
          ...
        ...
        ManualInstallation.htm
      * #.#.#.#.htm
      * Attributions.htm
      * CC-BY-ND-4.0.txt
      * changelog.md
      * Proton.version
      * readme.htm
      ...
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [BobCat Industries (BOB)](https://www.curseforge.com/kerbal/ksp-mods/BobCatInd)