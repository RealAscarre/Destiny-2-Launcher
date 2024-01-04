# Destiny-2-Launcher
A launcher for Destiny 2 to open the game from Steam and Epic Games without multiple Icons.

**Preview**

![Destiny 2 Launcher](https://github.com/RealAscarre/Destiny-2-Launcher/blob/main/Preview/preview.png)


# How to install Destiny 2 for both Steam and Epic Games?

Incase if you bought some dlc from steam during sale and got other dlc from epic games you might find yourself in a difficult position to play the game from both epi and steam in one pc.
I have a solution for that, you will install the game for both steam and epic games but it will only take 120 gb and not 240 gb for both steam install and epic install.

To install form both platforms you just need to follow this few simple steps:
```
1. Uninstall the gmae completely from you PC (only if it was installed from steam).
2. Install the fresh game from Epic Games.
3. Now locate your Game files from Epic store in your harddrive.
4. Once you are in the folder (should be Destiny2), open the folder named 'packages' and copy the path from the address bar above.
5. Now locate your steam folder (where steam is installed, usually its 'C:\Program Files (x86)\Steam'
6. Now navigate into the 'steamapps' then 'common' folder.
7. Now create a new folder and name it as 'Destiny 2'.
8. Now copy the path of the folder 'Destiny 2' and add '\packages' at the end. (If your steam is installed in 'C:\Program Files (x86)\Steam' then it should look like this - 'C:\Program Files (x86)\Steam\steamapps\common\Destiny 2\packages').
9. Now open command prompt or power shell then type 'New-Item -ItemType SymbolicLink -Path "EPIC_PATH_COPIED_AT_STEP_4" -Target "STEAM_PATH_COPIED_AT_STEP_8"'. (so it should be like this so far - New-Item -ItemType SymbolicLink -Path "C:\Program Files (x86)\EpicGames\Download\Destiny2\packages" -Target "C:\Program Files (x86)\Steam\steamapps\common\Destiny 2\packages").
10. Now press enter and it shouldn't show any errors.
11. Open steam and download the Destiny 2 Game.
12. It will first validate the game files but unfortunately it will still download the game files of 120 gb. But after installation is complete, the file size for steam install be around ~135 mb and epic games be around ~120 gb.
```
