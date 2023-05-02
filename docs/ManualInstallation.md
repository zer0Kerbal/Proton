---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.0.0
Протон (Proton)
created:01 May 2023
updated:

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->

<script src="https://kit.fontawesome.com/0ea5493613.js" crossorigin="anonymous"></script>
<i class="fa-solid fa-helmet-safety fa-beat-fade fa-3x" style="--fa-beat-fade-opacity: 0.1; --fa-beat-fade-scale: 1.25;color: #FF8200" ></i>

## [Протон (Proton)][mod]

[Home](./index.md)

Soviet Протон (Proton) expendable launch system

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
    + [BobCatInd][BOB]
      + [Agencies]
        ...
      + [Flags]
        ...
      + [Localization]
        ...
      ...
      + [SovietPack]
        + [Proton][mod]
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

* [BobCat Industries (BOB)][BOB]

THIS FILE: CC BY-ND 4.0 by zer0Kerbal
  used with express permission from zer0Kerbal

[BOB]: https://www.curseforge.com/kerbal/ksp-mods/BobCatInd "BobCat Industries (BOB)"
[mod]: https://www.curseforge.com/kerbal/ksp-mods/Proton "Протон (Proton)"