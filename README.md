# HL2:DM Gameplay Server Settings
This is a compilation of various Half-Life 2: Deathmatch gameplay settings that have been commented on. This is intended for both modding and historical reasons.

These settings, by default, are decoupled into categories, allowing users to quickly mix and match settings.

# Requirements
* [SourceMod](https://www.sourcemod.net/downloads.php?branch=stable)
* [MetaMod](https://www.sourcemm.net/downloads.php?branch=stable)

# Instructions
1. Copy and paste this to to hl2mp\cfg
2. Execute the config by typing `exec foldername/foldername_*.cfg`
3. Restart the map!

# Reset Values to Default
You'll need to reset a category's settings by typing `exec foldername/foldername_default.cfg`

## Getting server settings
If the settings aren't listed here, there are ways of getting a server's settings outside of asking the admin.
Consult [this GitHub's wiki page](https://github.com/ClangClangBattarang/HL2DM-Server-CVars/wiki/Finding-game-settings) for more info. 

# Other Recommended Server Stuff
## Server Plugins
* [HL2DM Fix](https://github.com/utharper/sourcemod-hl2dm#hl2dmfix) - Part of the XMS plugin suite that not only fixes most phyiscs problems, it also allows server admins (and cheating, insecure listen servers) to change fall damage maximum by using `mp_falldamage`.
* [Faster Chargers](https://forums.alliedmods.net/showthread.php?t=274722) - Used to control charger use speed.

# Credits
**Xeogin** - Stole some stuff from [his server config](https://github.com/Xeogin/xeogin.github.io/tree/master/hl2mp).
