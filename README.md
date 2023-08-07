### UIF Discord Rich Presence Plugin
UIF server San Andreas Multiplayer rich presence plugin powered by Lua and Moonloader.<br>
This repository is <b>archived</b> and is no more being maintained by me, feel free to fork your own and edit as you wish.<br><br>
If you have any questions related to this plugin then feel free to contact me on Discord (<b>@renisal</b>)
#
### Requirements
- [ASI Loader](https://www.gtagarage.com/mods/show.php?id=21709)
- [Moonloader](https://gtaforums.com/topic/890987-moonloader/)
- [SAMPFUNCS](https://libertycity.net/files/gta-san-andreas/151974-sampfuncs-v.-5.4.1.-final.html)
#
### Installation
Make sure to have the prerequisites installed which are mentioned above.<br>
Download and extract the contents of <b>[release](https://github.com/renisal/uif-discord-plugin/releases/download/stable/release.zip)</b> into your moonloader's directory.
#
### Screenshots
![Screenshot](https://i.imgur.com/6D2B5Eu.png) ![Screenshot](https://i.imgur.com/89CpqgK.png)
#
### RPC Values

While these are the values by default, you are free to edit the script as you like<br>

| RPC Value | Information |
| ------------- | ------------- |
| **FREEROAM & OTHER MODES**  | ___________  |
| Large Image  | UIF's logo  |
| Large Image Text  | PlayerName(ID)  |
| Small Image  | Held weapon's icon  |
| Small Image Text  | UIF Server IP  |
| Details(1)  | Player's state (Driving/Walking)  |
| Details(2)  | Current mode with players  |
| **FALL MODE** | ___________  |
| Large Image  | Current Map icon  |
| Large Image Text  | PlayerName(ID)  |
| Small Image Text  | Player's state (Lost/Standing)  |
| Details(1)  | Current Fall Map name  |
| Details(2)  | Current mode with players |
#
### Library

If you want to learn more about SA-MP moonloader & Lua and what can you display in your plugin:<br>
- [Lua Reference Manual](https://www.lua.org/manual/5.4/)
- [Moonloader Wiki](https://wiki.blast.hk/)
- [Moonloader Scripting API](https://wiki.blast.hk/moonloader/scripting-api)
- [Discord RPC](https://github.com/discord/discord-rpc)
