## How to install my assets

#### Structure of asset archive

To install you should download archive of branch by clicking [download](https://github.com/URAKOLOUY5/SourceMaps/archive/assets.zip)

After you have downloaded the archive, there will be the necessary folders:

![](https://cdn.discordapp.com/attachments/619231812987650059/665626496857145354/unknown.png)

Folder **assets** is a root folder. It contain **gamename** и folder named **mod**. **Mod** contain assets used by mod's maded by [PythSource](https://github.com/pythsource).

#### Installing assets to your Valve Hammer Editor

Once you have checked the structure of the archive and selected the neccesary asset, you need to install them in your SDK editor. 

First you need to open a folder with the game that is located in `steamapps`. In this folder you find the game (ex: Half-Life 2) and one of the games opens. For example, if your editor uses `ep2` you open it. In it you find the file `gameinfo.txt`.  Next, look for a line:

![](https://cdn.discordapp.com/attachments/619231812987650059/665629168066887703/unknown.png)

Add new line, like this:

![](https://cdn.discordapp.com/attachments/619231812987650059/665629503338315776/unknown.png)

When you have added this line, save the file. And go back to the main game folder (ex: **Half-Life 2**).
There, create a new folder with the same name as you specified after `game+mod`. In our case, `urakolouy5_gmodassets`. Next, open the archive and browse to the assets folder. Open the game and content you want to the map and copy it into the created folder.

Finally, you can use my assets in your SDK!
