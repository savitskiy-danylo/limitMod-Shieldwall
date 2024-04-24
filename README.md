# limitMod-Shieldwall
This mod for the game Shieldwall increases the army limit to 100.

# How to install
1. Download and unzip mod.
2. Move files from Mod\Binaries\Win64 to Shieldwall\Shieldwall\Binaries\Win64.
3. Replace the LoaderPath in the ModLoaderInfo.ini with the path to this file (it should look like this: CurrentPath\UnrealEngineModLoader.dll).
4. You can choose to enable (1) or disable (0) the console that appears when you start the game.
5. Move the files from Mod\Content\Paks\LogicMods to Shieldwall\Shieldwall\Content\Paks\LogicMods. (Create a LogicMods folder if it doesn't exist already.)
6. Here you go!

# Questions
* Why 100?
	* If on one soldiers count more than ~200-300, game starts to lag badly.
* Does this mod work whith Multiplayer?
	* Yes!
* All players should have this mod installed to play in Muliplayer?
	* No, it should be enough if host have this mod installed.
* I am getting "Fatal Error" when connect to Multiplayer lobby.
	* If you and host have this mod, than this could be a cause. Just delete LimitMod.pak file from Mod\Content\Paks\LogicMods while playing in that lobby.

# 3rd Party Software
  * [Unreal Engine Mod Loader](https://github.com/RussellJerome/UnrealModLoader/tree/main)