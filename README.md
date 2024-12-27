<h1 align="center">
  <b>shadPS4 Game Compatibility</b>
</h1>

### Rules:

- Only publish results from major [**shadPS4 releases**](https://github.com/shadps4-emu/shadPS4/releases) (e.g. 0.5.0).
- Make sure you put all the necessary information: **Title**, **Game ID** and **Version**.
- Don't edit posts, just reply to them. That way we can check what's changed from previous version.
- Since compatibility between different OS varies, we allow one report per system-OS (Windows, Linux and macOS). So duplicate entries can exist if they are for different OS.
- You can publish the same game only if the CUSA is different (e.g. Bloodborne = CUSA00900 & CUSA03173)

### To see where the status is for the games:

- [**Nothing**](https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-nothing)
- [**Boots**](https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-boots)
- [**Menus**](https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-menus)
- [**Ingame**](https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-ingame)
- [**Playable**](https://github.com/shadps4-emu/shadps4-game-compatibility/labels/status-playable)

## Informations

shadPS4 can load some modules in **LLE** mode, some are necessary and some have **HLE** replacements.\
The following firmware modules are supported and must be placed under `user/sys_modules` folder.\
Tested FW modules are from **11.00**.

- **libSceNgs2.sprx**
- **libSceFiber.sprx**
- **libSceUlt.sprx**
- **libSceJson.sprx**
- **libSceJson2.sprx**
- **libSceLibcInternal.sprx**
- **libSceDiscMap.sprx**
- **libSceRtc.sprx**
- **libSceJpegEnc.sprx**
- **libSceCesCs.sprx**
- **libSceFont.sprx**
- **libSceFontFt.sprx**
- **libSceFreeTypeOt.sprx**

> [!IMPORTANT]
> The above modules are required to run the games properly and must be extracted from your PS4.
> **We do not provide any information or support on how to do this**.
