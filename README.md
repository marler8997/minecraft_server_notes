

> NOTE: refer to this page for more detailed instructions and questions https://minecraft.gamepedia.com/Tutorials/Setting_up_a_server

Whether you are installing the server with forge (which lets you add mods) or the vanilla server, make sure you have java installed.

# Option 1: Install Server with Forge (can use mods)

* Download the forge installer

http://files.minecraftforge.net/

* Run the forge installer, select "Install Server" and pick a directory to install your server
* Double click the "forge...jar" file to generate the config files.
* Modify eula.txt by setting "eula=true"
* From Command line: launch server with these options
```bash
# NOTE: nogui is optional
java -Xmx1024M -Xms1024M -jar forge-<VERSION>-universal.jar nogui
```
* Install any mods to the "mods" folder

# Option 2: Install Vanilla Server

* Download Minecraft Server (download it to it's own directory)

  - Download page: https://minecraft.net/en-us/download/server/

  - Example Download: https://launcher.mojang.com/v1/objects/3737db93722a9e39eeada7c27e7aca28b144ffa7/server.jar

* Launch the server once to generate config files (you can just double click it, no options necessary)
* Modify eula.txt by setting "eula=true"
* From Command line: launch server with these options
```bash
# NOTE: nogui is optional
java -Xmx1024M -Xms1024M -jar server.<VERSION>.jar nogui
```