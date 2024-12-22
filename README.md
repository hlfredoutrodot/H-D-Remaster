# Hidden and Dangerous Remaster
## What's that
H&D Remaster is a version of H&D Deluxe which is mixed with H&D Original files and others improvement made by the community and me. The aim of this version is to create a fluid game experience playable on modern os and hardware using moderns drivers without any bugs.


## Improvement list

**binary improvements (thanks to Daemonsteufel):**

 - patched enemies fast fire bug
 - added save in addons
 - added save in multiplayer
 - removed advertising splash screen
 - removed ad screen for HD2
 - FFF weapons can be chosed in addons
 - AI can't shot friend by error
 - friend AI don't change weapon without order
 - friend AI don't chase ennemy without order
 - weapons centered in fps view
 - doors can be closed again
 - cheatcodes newlife and fullhands usable in multiplayer
 - wide screen correction
 - added a third enemy group civils running away when there is explosion
 - some game editor additionnal functions


**General improvement**:

 - uncensored the game
 - uncensored the game menus
 - patched the multiplayer on modern windows (applied [HDDMultiplayerPatch](https://github.com/WJLiddy/HDDMultiplayerPatch))
 - Original opus musics
 - added gun holes
 - added body gibs
 - changed knife animations
 - added an auto-updater which ask for an update
 - changed the game icon to the original
 - Added the right 3ds max plugins files in the game directory
 - removed dead body optimisation in Germany6 due to the performances of new computers
 - Added [DXVK](https://github.com/doitsujin/dxvk) which permit the game to be played on modern graphic cards with Vulkan
 - added individual allied faces from H&D Original
 - reworked the setup to made the game standalone of the original game
 - added a launcher which allow advanced functionnalities like language change, auto-login and auto-host


## Download

1. Download .7z archive [here](https://mega.nz/file/VaVz2BwA#9XZTveP09DfiiVp0Um03Z2v5WWnZPxFP5VNOw92uO7Q)

### Antivirus troubleshooting
The installer of the remaster was created using bat2exe converter, so game.exe is not signed by microsoft and it can cause some mistakes. If you won't bypass your antivirus, just launch the game by hde.exe (please keep in mind that this method don't allow you to have custom languages or custom user auto-login)


## Install on an existing Hidden and Dangerous Deluxe installation

Download the archive in the download section, extract it (if asked the extracted files must replace the existing) into your h&d deluxe directory (for me: C:\Program Files (x86)\Take2\Hidden and Dangerous Deluxe). This must be extracted next to the bin and data folders.

After this, you can launch the game with game.exe and not \bin\hde.exe, I let you create the shortcut.

Please consider that this installation procedure may cause some conflicts because it's installed in an admin-righted folder but the program is launch with user permissions.


## External Settings (language & username)

The files in \bin\startconfig\ are configuration files which stores the language settings and the username.


### Language

Here a list of supported language (just replace English by another languages in this list):
 - English
 - German
 - French
 - Spanish
 - Italian


### Username

The username file set the username will be used to launch the game and it also set the multiplayer username


### DoAutoHost

Settings not really useful, may cause some bugs. You can use it to launch the game directly in host mode. Replace it by another text than "No" and it will be taken as a "Yes"
