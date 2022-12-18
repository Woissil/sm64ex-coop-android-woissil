# sm64ex-coop
Unsanctioned WIP fork for Android. Online multiplayer mod for SM64 that synchronizes all entities and every level for multiple players. Fork of [sm64pc/sm64ex](https://github.com/sm64pc/sm64ex). Contains code copied from [AloXado320/sm64ex-alo](https://github.com/AloXado320/sm64ex-alo), [VDavid003/sm64-port-android](https://github.com/VDavid003/sm64-port-android), [VDavid003/sm64-port-android-base](https://github.com/VDavid003/sm64-port-android-base), and [porcino/sm64-port-android](https://github.com/porcino/sm64-port-android).

Feel free to report bugs and contribute, but remember, there must be **no upload of any copyrighted asset**. 
Run `./extract_assets.py --clean && make clean` or `make distclean` to remove ROM-originated content.

## How to Play on Android

[Click here to read the guide for Android](README_android.md).

[Click here to build the `.apk` from a non-Android device](https://github.com/robertkirkman/sm64ex-coop-android-base) (more complicated for now). 

What this can do (build featured in video is old):

[![demo](https://i.ytimg.com/vi/jv2kotnoX10/maxresdefault.jpg)](https://www.youtube.com/watch?v=jv2kotnoX10 "sm64ex-coop android (zink + Xwayland)")

What works:

✅ NO root, chroot, proot or custom graphics driver required

✅ Direct connection - client and server ([VPN guide here](README_vpn.md))

✅ GPU acceleration

✅ SurfaceFlinger SDL2 backend

✅ Normal audio

✅ (most) DynOS and Lua mods

✅ Touch controls (buggy)

✅ Fullscreen

✅ External gamepads

What doesn't work:

❌ Shell Rush and Arena

❌ In-game chat (no button/binding for it yet)

❌ Texture packs that are too intensive (like full-res Render96)

❌ Inconsistent crashes in star selects and entering Peach's Castle

❌ Discord

❌ BASS audio

## How to Play

[Instructions on how to play are available on the wiki.](https://github.com/djoslin0/sm64ex-coop/wiki/How-to-Play)

- The easiest way is to download [coop-compiler](https://github.com/coop-compiler/coop-compiler/releases/latest/download/coop-compiler.exe)

## Goal (accomplished)
Create a mod for the PC port where multiple people can play online together.

Unlike previous online attempts, this one synchronized enemies and events. This allows players to be interacting with the same world at the same time.

## Lua
sm64ex-coop is moddable via lua, similar to how Roblox and Gmod works. To get started, click [here](docs/lua/lua.md) to see the lua documentation

## Discord
[https://discord.gg/TJVKHS4](https://discord.gg/TJVKHS4)
