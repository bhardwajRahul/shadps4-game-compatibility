# shadPS4 Game Compatibility

This is the compatibility tracker for PlayStation 4 games on shadPS4.

Rules:

- Only publish results from major [**shadPS4 releases**](https://github.com/shadps4-emu/shadPS4/releases) (e.g. 0.5.0).
- Make sure you put all the necessary information: Title, Game ID and Version.
- Don't edit posts, just reply to them. That way we can check what's changed from previous version.
- Since compatibility between different OS varies, we allow 1 report per system-OS (Windows, Linux and macOS). So duplicate entries can exist if they are for different OS.

# Info

shadPS4 can load some modules in LLE mode, some are neccesary and some have HLE replacements. The folllowing firmware modules are supported and must be placed under `user/sys_modules` folder. Tested FW modules are from 11.00.

- libSceNgs2.sprx
- libSceFiber.sprx
- libSceUlt.sprx
- libSceJson.sprx
- libSceJson2.sprx
- libSceLibcInternal.sprx
- libSceDiscMap.sprx
- libSceRtc.sprx
- libSceJpegEnc.sprx
- libSceCesCs.sprx
- libSceFont.sprx
- libSceFontFt.sprx
- libSceFreeTypeOt.sprx

Above modules should be extracted from your PS4. We don't provide any info or support of how to do it.
