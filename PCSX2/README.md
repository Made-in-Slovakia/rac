# PCSX2

My creations for [PCSX2](https://pcsx2.net) emulator.

## Disclaimer

Some of these creations are experimental. They may corrupt your saves and save states. Do not use them with your standard saves and always use new save or backup them before use.

``Use at your own risk``

I develop and test with PAL (European) versions of the games. I try to provide NTSC (North America) versions when possible, but they may not always work properly.

Some also may be marked as work in progress (WIP), see description for details.

If you encounter any issue, please report it via [GitHub Issues](https://github.com/Made-in-Slovakia/rac/issues) or DM me.

## Update notifications

If you want receive notification about updates and also about new mods, you can use [Atom/RSS feed for this repository](https://github.com/Made-in-Slovakia/rac/commits/main.atom). It is standard Atom/RSS feed source and can be used with most of news reader apps.

Link to Atom/RSS feed: [https://github.com/Made-in-Slovakia/rac/commits/main.atom](https://github.com/Made-in-Slovakia/rac/commits/main.atom)

## Patches / Cheats / Mods

### How to install

Download the `pnach` file for your game version and save it to the folder `pcsx2\cheats` in your user `Documents` folder. It schould be already created by PCSX2.

Cheats/mods can be enabled/disabled from the `Cheats` page of the game properties window, and will only be applied if the `Enable Cheats` setting is enabled. This setting can be enabled globally from the `Emulation` page of the settings window, or on a per-game basis from the `Cheats` page of the game properties window (recommended).

![Enable cheats for a specific game](resources/menu-1.jpg "Enable cheats for a specific game")

### Ratchet & Clank 2 (Going Commando)

#### Ratchet has a small head

Shrinks Ratchet's head by `0x10`, which is just about right. If you want to shrink it more, change `3C013F50` in pnach file to `3C013F20` and reload the game from save.

#### Old School Ratchet

Flashback to Ratchet and Clank 1 with this retro Ratchet getup.

Mod replaces `Commando Suit` and `Snow Dude` (a.k.a. Snowman) skin (avaiable in Special menu). While Commando Suit still have helmet and boots (I left them here because of Megacorp policies for safety), Snow Dude skin is replaced with Ratchet skin you know from R&C1. Because it is skin, it does not affect protection from curretly equipped armor. And do not worry, the skin is enabled even if you did not unlock it in-game.

![Old School Ratchet](resources/screenshot-1.jpg "Old School Ratchet")

Installation: In addition to `pnach` file, download files in `textures` folder and save them to the folder `pcsx2\textures` in your user `Documents` folder. It schould be already created by PCSX2. Then enable PCSX2 feature `Texture replacement` for Ratchet & Clank 2 game.

![Enable texture replacement for a specific game](resources/menu-2.jpg "Enable texture replacement for a specific game")

#### Old School Ratchet - Reloaded

Updated version of `Old School Ratchet` mod where equiped boots (gadgets) and O2 mask are shown when they are equipped or used.

![Old School Ratchet - Reloaded](resources/screenshot-2.jpg "Old School Ratchet - Reloaded")

### Ratchet & Clank 3 (Up Your Arsenal)

#### Fix for armor boots

Game contains a bug that causes the default boots are displayed instead of the boots for equipped armor. The bug appears after using Gravity or Charge Boots for the first time. This mod will fix it.

``Activate only after acquiring Gravity or Charge Boots and equipping them at least once, otherwise the emulator will crash.``

![Ratchet's new boots](resources/screenshot-3.jpg "Ratchet's new boots")

#### Fix for armor boots - Reloaded

More complex version of `Fix for armor boots`. Use `Fix for armor boots` mod if this one does not work. 

``When you activate this mod for the first time, load the game from the memory card, otherwise the emulator may crash. After the game is loaded from the memory card, it is possible to use the save states.``
