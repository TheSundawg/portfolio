##### Link to Original File: [README.md](README.md)

# About
This repository is primarily for users to download custom maps for Minecraft.

## Software Requirements
The following is required to access the packaged data.
* [Minecraft](https://www.minecraft.net/en-us/download)
* [WorldPainter](https://www.worldpainter.net/) (Only exports to Java edition)

    ### Optional
  The following app is necessary only if you intend to convert world data between the Java and Bedrock editions.
  - [Chunker](https://www.chunker.app/)

    #### Known Issues with Conversion
    There are several known issues that occur when converting world data. These issues stem from how Minecraft encodes world data. They cannot be fixed and must be accounted for when converting.
    - Only world data that has been **explored within the game** will be encoded between conversions. Any region that has **not** been explored will be randomly generated during gameplay and **will not** match the data found on the map.
## How to Use this Repository
1. Download the .zip file.
2. Extract the file to a local folder.
3. Open WorldPainter.
4. Under "File" select open and navigate to your extracted file.
5. Under "File" select "Export to Minecract Map."
6. Set the world size to "4000 blocks."
7. When asked for an export location, find the "saves" subfolder for Minecraft. (```%appdata%/.minecraft/saves``` for Windows)
   ### Optional Steps for Conversion
1. Open the saved world in _**creative mode**_ in Minecraft.
2. Explore the region of the world you will convert.
        For larger worlds, use an automatic chunk loader.
3. Save and exit the game.
4. Launch Chunker and open the world file from your "saves" folder.
5. Convert the file to the selected Minecraft edition.
6. Once converted, export to the save folder. (```%localappdata%\Packages\Microsoft.MinecraftUWP_8wekyb3d8bbwe\LocalState\games\com.mojang\minecraftWorlds``` for Windows)
