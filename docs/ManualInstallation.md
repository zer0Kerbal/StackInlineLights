---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.1.8.1
Stack Inline Lights (SIL)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# Stack Inline Lights (SIL)

[Home](./index.md)

***BLURB***

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `ASET` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/ASET/StackInlineLights`
* Extract the package's `ASET/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/ASET` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/ASET/StackInlineLights`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/ASET/StackInlineLights`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/ASET/StackInlineLights`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [ASET]
      + [Agencies]
        ...
      + [Flags]
        ...
    + [StackInlineLights]
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
      * #.#.#.#.htm
      * ASET.version
      * Attributions.htm
      * CC-BY-NC-SA-3.0.txt
      * changelog.md
      * ManualInstallation.htm
      * readme.htm
    ...
    * [Module Manager /L][mml] or [Module Manager][mm]
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* *either*
  * [Module Manager][mm]
  * [Module Manager /L][mml]

[mm]: https://forum.kerbalspaceprogram.com/index.php?/topic/50533-*/ "Module Manager"
[mml]: https://github.com/net-lisias-ksp/ModuleManager "Module Manager /L"

<!-- this file CC BY-ND 4.0 by zer0Kerbal -->