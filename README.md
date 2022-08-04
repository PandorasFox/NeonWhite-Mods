# NeonWhite Mods

## Installation Prerequisites

You need to install both MelonLoader (a generic modloader for all Unity games) and MelonPreferences (the mod config menu for MelonLoader, which itself is a mod) in order to use any of my mods.

1. Download [MelonLoader](https://github.com/LavaGang/MelonLoader/releases/latest) and install it onto your `Neon White.exe`.
2. Run the game once. This will create required folders; you should see a splash screen if you installed the modloader correctly.
3. Download the **Mono** version of [Melon Preferences Manager](https://github.com/sinai-dev/MelonPreferencesManager/releases/latest), and put the .dlls from that zip into the `mods` folder of your Neon White install (e.g. `SteamLibrary\steamapps\common\Neon White\Mods`)
    * The preferences manager is *required* to use the powertools mod - it is how you turn parts of it on and off. Everything is off by default.
    * The default keybind for the mod preferences menu is F5; you can easily rebind this.
    * The IL2CPP version **WILL NOT WORK**; you **must** download `MelonPreferencesManager.Mono.zip`. 

At this point, you can install any of my mods (or any other MelonLoader mods) for Neon White by dropping their .dll file into the `mods` folder.

## List of Mods

* [Puppy Powertools](https://github.com/PandorasFox/NeonWhite-PuppyPowerTools)
  * Collecton of small allowed-for-speedrunning tidbits (speedometer, chapter timer, vfx toggles and minor visual customizations)
* [Neon TAS kit](https://github.com/PandorasFox/Neon-TAS)
  * Input record/replay kit. Only works reliably when vsynced on a monitor running at 60Hz.
* [Mikey Practice Mode](https://github.com/PandorasFox/NeonWhite-MikeyMode)
  * Lets you practice ILs as if they were in Mikey Rush
* [Debug Kit](https://github.com/PandorasFox/Neon-White-DebugMenu)
  * Handful of debug utilities (timescaling, card spawning, enemy AI disabling, collision box visualization)

### Additional Notes

You should probably add `--melonloader.hideconsole` to your game launch properties (right click the game in steam -> properties -> launch options at the bottom of that window) to hide the console that melonloader spawns. You really only need that if you're a mod developer; it's a weird default.

![image](https://user-images.githubusercontent.com/3235827/181994781-af470314-9836-49f4-beec-abdf1f9e37ea.png)

