---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- 
hdr-changelog.md v1.0.0.0
Протон (Proton)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | Протон (Proton)                                                   |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-4.0                                                      |
| author     | BobCat, DECQ, Dragon01, and zer0Kerbal                            |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/216980-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/Proton)                 |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/Proton)               |

## Version 3.9.99.0-release `<Thank you BobCat, CrashnBurn, DECQ, and Dragon01>` edition

* Released
  * 02 May 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

* 📌 Pinned
  * Dependencies:
    * [BobCat Industries (BOB)](https://www.curseforge.com/kerbal/ksp-mods/BobCatInd)

## Adopted by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 3.9.99.0

* Update
* Lint
* and so much more
* DRAG_CUBES
* Cargo/Inventory
* Modernize
* Convert all textures to dds
* Add modcons to parts
* Localization
  * English

### Changes 3.9.99.0

### Archival Releases

* 3.0.0.0-release
* 2.0.0.0-release
* 1.9.1.1-release
* 1.0.0.0-release
* closes #7 - Archival Releases

### Part Asset Updates

* create Assets/ folder
* convert
  * from mesh to MODEL {}
  * from .mbm/.tga/.png to .dds
  * 8.5mb --> 1.95mb --> 2.83mb
* rename
  * remove space and underscores
  * models to unique names
  * textures to unique names
  * Stages
    * model000--> proton00
    * model001 --> proton01
  * Bits
    * model000 --> proton10
    * model001 --> proton11
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate
  * assets to Assets/
  * part.cfg to Parts/
* eliminate
  * duplicate textures
  * duplicate models
* rename parts to standardized names (e.g. nrf-)
* Add
  * <ghostParts.cfg> v2.0.0.0
  * in order to prevent name changes from breaking compatibility
* closes #9 - Part Asset Updates

### Compatibility 3.9.99.0

* Update
  * <RealismOverhaul.cfg> v3.9.99.0
    * update part names
    * minor linting

### Localization 3.9.99.0

* Create
  * Localization/
    * <en-us.cfg>
    * [readme.md] v2.1.2.0
    * [quickstart.md] v1.0.1.1
* closes #16 - English <en-us.cfg>
* closes #33 - Part Localization
* closes #34 - Part Tags
* closes #8 - Create Localization directory and contents
* updates #15 - Localization - Master

### Documentation

* Create
  * GitHub Pages
  * docs/
    * [`_config.yml`]
    * [404.md] v1.0.3.2
    * [Assembly.md] v1.0.1.0
    * [Attribution.md] v1.0.9.0
    * [LegalMumboJumbo.md] v1.0.6.0
    * [Localizations.md] v1.1.9.0
    * [ManualInstallation.md] v1.1.9.1
    * [Marketing.md] v1.0.3.0
    * [Notices.md] v1.0.2.0
    * [PartsCatalog.md] v1.1.4.3
    * [Why.md] v1.1.0.1
  * HeroLogo.png
  * copy/convert to HeroLogo.jpg
* Add
  * [Proton.cfg] v1.0.0.0
    * adds localized tags to parts
* closes #5 - Create GitHub Pages
* closes #6 - Create HeroLogo.png
* closes #10 - Create <Proton.cfg>

### Status 3.9.99.0

* Issues
  * closes #1 - Протон (PROTON) 3.9.99.0-adoption `<Thank you BobCat, CrashnBurn, DECQ, and Dragon01>` edition
  * closes #2 - 1.1.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 1.1.99.0 Create Documentation
  * closes #4 - 1.1.99.0 Create Social Media Presence

---

## Version 3.0.0.0-release `<Archival>` edition

* Released
  * 26 Feb 2019
  * for Kerbal Space Program 1.6.1
  * by BobCat, CrashnBurn, DECQ, Dragon01, and MacLucky
  * maintenance by krakra23 and albertovillalobo

* no changelog

* Issues
  * closes #14 - 3.0.0.0-release
  * closes #7 - Archival Releases

---

## Version 2.0.0.0-release `<Archival>` edition

* Released
  * ?
  * for Kerbal Space Program 1.0.0.0?

* no changelog

* Issues
  * closes #13 - 2.0.0.0-release
  * updates #7 - Archival Releases

* Last released by DECQ and Dragon01
* From BobCat Industries Soviet Pack

---

## Version 1.9.1.1-release `<Archival>` edition

* Released
  * ?
  * for Kerbal Space Program ?

* parts renamed (internally) and things moved around and more.
* no changelog

* Issues
  * closes #12 - 1.9.1.1-release
  * updates #7 - Archival Releases

---

## Version 1.0.0.0-release `<Archival>` edition

* Released
  * 06 Nov 2014
  * for Kerbal Space Program 0.23.5
  * by BobCat and CrashBurn

* no changelog

* Issues
  * closes #11 - 1.0.0.0-release
  * updates #7 - Archival Releases

---