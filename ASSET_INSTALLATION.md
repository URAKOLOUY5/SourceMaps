## How to install my assets

### Structure of asset archive

To install you should download archive of branch by clicking [download](https://github.com/URAKOLOUY5/SourceMaps/archive/master.zip)

After you have downloaded the archive, there will be the necessary folders:

![](https://cdn.discordapp.com/attachments/619231812987650059/701137988771643402/unknown.png)

Theres folder **assets** - is a root folder. It contain **gamename** (for example `mapbase_episodic`). 



Once you have checked the structure of the archive and selected the neccesary asset, you need to install them in your SDK editor. 

### Installing assets to your Valve Hammer Editor (Vanilla Half-Life 2 or VHE for Half-Life 2 but used for Garry's Mod)

This is categorically not suitable for maps made for U5Maps or modifications on Mapbase (below is the link to download U5Maps).

![](https://camo.githubusercontent.com/92fb84a78bc5254d72a99d9b9c04d48e7c1137cd/68747470733a2f2f646576656c6f7065722e76616c7665736f6674776172652e636f6d2f772f696d616765732f632f63622f5761726e696e672e706e67) **Some textures may not work for the vanilla version of Half-Life 2 (e.g. assets from the mapbase_episodic folder)!!!**

First you need to open a folder with the game that is located in `steamapps`. In this folder you find the game (ex: Half-Life 2) and one of the games opens. For example, if your editor uses `ep2` you open it. In it you find the file `gameinfo.txt`.  Next, look for a line:

![](https://cdn.discordapp.com/attachments/619231812987650059/665629168066887703/unknown.png)

Add new line, like this:

![](https://cdn.discordapp.com/attachments/619231812987650059/665629503338315776/unknown.png)

*If you are interested in editing gameinfo.txt, please visit the [Valve's wikipedia page](https://developer.valvesoftware.com/wiki/Gameinfo.txt)*

When you have added this line, save the file. And go back to the main game folder (ex: **Half-Life 2**).
There, create a new folder with the same name as you specified after `game+mod`. In our case, `urakolouy5_gmodassets`. Next, open the archive and browse to the assets folder. Open the game and content you want to the map and copy it into the created folder.

Finally, you can use my assets in your SDK!

### Installing assets to your Mapbase (Only U5Maps)


All content is already packaged in the U5Maps map-base.

You can download U5Maps [here](https://github.com/URAKOLOUY5/mapbase_u5_base/releases)

