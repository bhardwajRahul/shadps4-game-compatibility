<h1 align="center">
  <b>shadPS4 Game Compatibility</b>
</h1>

<h2 align="center">
<a href="https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-playable">
    <img src="https://img.shields.io/github/issues-search/shadps4-emu/shadps4-game-compatibility?query=is%3Aopen+label%3Astatus-playable&style=for-the-badge&color=8BA503&label=Playable"/>
<a href="https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-ingame">
    <img src="https://img.shields.io/github/issues-search/shadps4-emu/shadps4-game-compatibility?query=is%3Aopen+label%3Astatus-ingame&style=for-the-badge&color=F3BB00&label=Ingame"/>
<a href="https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-menus">
    <img src="https://img.shields.io/github/issues-search/shadps4-emu/shadps4-game-compatibility?query=is%3Aopen+label%3Astatus-menus&style=for-the-badge&color=FF5C1A&label=Menus"/>
<a href="https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-boots">
    <img src="https://img.shields.io/github/issues-search/shadps4-emu/shadps4-game-compatibility?query=is%3Aopen+label%3Astatus-boots&style=for-the-badge&color=A7001E&label=Boots"/>
<a href="https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-nothing">
<img src="https://img.shields.io/github/issues-search/shadps4-emu/shadps4-game-compatibility?query=is%3Aopen+label%3Astatus-nothing&style=for-the-badge&color=black&label=Nothing"/>
</h2>

- **status-playable**: Games that can be run without any issues.
- **status-ingame**: Games that can reach gameplay but have issues.
- **status-menus**: Games that can reach the menu but freeze/crash when trying to proceed further.
- **status-boots**: Games that show any visual/audio output but freeze/crash before reaching the menu.
- **status-nothing**: Games that crash when trying to launch or only show a black screen.

## Rules:

- Only publish results from major [**shadPS4 releases**](https://github.com/shadps4-emu/shadPS4/releases) (e.g. 0.6.0).
- Make sure you put all the necessary information: **Title**, **Game ID**, **Game Version**, **Emulator Version**, **Compatibility Status** and **Operating System**.
- Don't edit posts, just reply to them. That way we can check what's changed from previous version.
- Since compatibility between different OS varies, we allow one report per system-OS (Windows, Linux and macOS). So duplicate entries can exist if they are for different OS.
- You can publish the same game only if the CUSA is different (e.g. Bloodborne = CUSA00900 & CUSA03173)

## Informations

shadPS4 can load some modules in **LLE** mode, some are necessary and some have **HLE** replacements.\
The following firmware modules are supported and must be placed under `user/sys_modules` folder.\
Tested firmware modules are from **11.00**.

<div align="center">

| Modules                 | Modules                 | Modules                 | Modules                 |  
|-------------------------|-------------------------|-------------------------|-------------------------|  
| libSceCesCs.sprx        | libSceDiscMap.sprx      | libSceFont.sprx         | libSceFontFt.sprx       |  
| libSceFreeTypeOt.sprx   | libSceJson.sprx         | libSceJson2.sprx        | libSceLibcInternal.sprx |  
| libSceNgs2.sprx         | libSceRtc.sprx          | libSceUlt.sprx          |                         |  

</div>

> [!Caution]
> The above modules are required to run the games properly and must be extracted from your PlayStation 4.\
> **We do not provide any information or support on how to do this**.
