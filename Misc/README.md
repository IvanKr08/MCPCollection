# Miscellaneous Files
## fernflower.jar

Fernflower 0.8.6 decompiler for MCP below 7.0a

## damt-0.1.jar

[Original source](https://www.minecraftforum.net/forums/mapping-and-modding-java-edition/minecraft-mods/mods-discussion/1291855-a-custom-tweaker-for-using-older-modloaders-in-the)

***Work from beta 1.7.3 up to release 1.6.2***

Fixes "URL is not hierarchical" exception and allows Modloader to work in new launchers

#### How to use

1. Go to \<***MC folder***\>\libraries and create directory "\\damt\\damt\0.1"
2. Put "damt-0.1.jar" into "\<***MC folder***\>\\libraries\\damt\\damt\0.1"
1. Install Modloader
2. Install mods
3. Open \<***You MC Version***\>.json file
   - Find _"libraries": \[_
	 - Add _"{"name": "damt:damt:0.1"}, "_ (Without quotes) after _\[_
   - Find _"minecraftArguments":_
     - Change _"${auth_player_name} ${auth_session} --gameDir ${game_directory} --assetsDir ${game_assets}"_ to _"${auth_player_name} ${auth_session} --gameDir ${game_directory} --assetsDir ${game_assets} --tweakClass damt.ModLoaderTweaker"_

#

TODO: Complete later
