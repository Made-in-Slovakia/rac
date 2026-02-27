# PCSX2

This recository contains some of my creations related to [PCSX2](https://pcsx2.net) emulator.

## Patches / Cheats

### Warning

``Use at your own risk``

These are experimental patches/cheats. They may break your saves. Do not use them with your standard saves and always use new save or do backup of your saves. This also apply for save states.

These are experimental patches/cheats. They may corrupt your saves and save states. Do not use them with your standard saves and always use new save or backup them before use.

### State

These patches/cheats are currently a work in progress (WIP) and are tested with PAL (European) versions of the games. Sometimes NTSC (USA) versions are also available, but may not always work properly.

### Installing cheat

Download and copy the `pnach` file to the folder `pcsx2\cheats` in your user `Documents` folder.

Cheats can be enabled/disabled from the `Cheats` page of the game properties window, and will only be applied if the `Enable Cheats` setting is enabled. This setting can be enabled globally from the `Emulation` page of the settings window, or on a per-game basis from the `Cheats` page of the game properties window.

### Additional details about cheats

#### Ratchet & Clank 2

##### Ratchet has a small head

Shrinks Ratchet's head by `0x10`, which is just about right. If you want to shrink it more, change `3C013F50` in pnach file to `3C013F20` and reload the game from save.
