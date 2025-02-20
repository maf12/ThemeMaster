# ThemeMaster
ThemeMaster is an EmulationStation theme manager for small screen devices (e.g. Chi, OGA, RGB10, RK2020, RG351p/m, RG351v and OGS, RGB10 Max) running ArkOS, RetroOZ or TheRA.

# Controls
## Navigation
- Controls are : d-pad to move, A to validate, B to select an item in radiolist and checklist.
- Select key exits ThemeMaster.
- You can force quit ThemeMaster by pressing Select + Start.

## Image viewer
- Controls are : X to quit displaying a picture, Y to rotate a picture.

# How it works
- Theme's update management is based on latest GitHub commit's date.
- Theme management is based on GitHub repository's name.
- Uninstaller allows removal of stock themes which you may not be able to reinstall via ThemeMaster.
- User's preferences are saved in the "ThemeMaster.cfg" file which is generated after first launch.
- Files within the "data" subfolder are automatically (re)generated by the application.

## GitHub Repository mode
In **GitHub repository** mode, ThemeMaster creates live theme’s collection by pulling information from a GitHub account based on repositories starting with "es-theme".
- You can change the account to be used from **ThemeMaster Settings** menu.
- The list of GitHub accounts to be used can be manually configured by editing the "collections" variable in "ThemeMaster.cfg" file. NB : before adding an account, please check that repositories are pre-set with the correct ES folder structure (as ThemeMaster relies on GitHub source).

## Theme Gallery mode
In **Theme Gallery** mode, ThemeMaster relies on information from [Emulationstation-OGA-Theme-Gallery](https://github.com/Jetup13/Emulationstation-OGA-Theme-Gallery) by [Jetup](https://github.com/Jetup13) to create a bespoke theme collection (allowing access from different GitHub accounts at once).
Collection is cached locally and updated at startup whenever new commit exists on [Emulationstation-OGA-Theme-Gallery](https://github.com/Jetup13/Emulationstation-OGA-Theme-Gallery) repository.

# Nota Bene
- Beware that name duplicates (between different GitHub accounts) is not managed ; this could lead to unwanted behaviour if you choose to swap between theme collections (e.g. replace a theme with another).
- Prerelease versions may have been barely tested, use at your own risk.

# Credits
ThemeMaster reused some external code to emulated keyboards and display pictures :
- 'controls' binary is based on [AnberPorts-Joystick](https://github.com/krishenriksen/AnberPorts-Joystick) by [Kris Henriksen](https://github.com/krishenriksen),
- 'image-viewer' binary is based on [Image Viewer](https://github.com/RICCIARDI-Adrien/Image_Viewer) by [Adrien Ricciardi](https://github.com/RICCIARDI-Adrien).

# Background
Original script [ArkThemes](https://github.com/TadMSTR/ArkThemes) was developed for [ArkOS](https://github.com/christianhaitian/arkos) by [TadMSTR](https://github.com/TadMSTR) based on [AnberPorts](https://github.com/krishenriksen/AnberPorts) with contributions from **choo t** and **JohnIrvine**.

Most evolutions have been initially implemented on [ArkThemes-fork](https://github.com/JohnIrvine1433/ArkThemes-fork) which has reached EOL following the release of ThemeMaster (new name suggested by **5uck3rpunch**).

# Installation
## ArkOS
Need to be on ArkOS 2021-02-13 (02132021) or newer.  
Place *ThemeMaster.sh* and *ThemeMaster* folder in `/roms/tools`.
NB : on RG351V, if SD2 is being used for roms, installation must be in `/roms2/tools/`.
Run ThemeMaster from ArkOS Options > Tools menu.

## TheRA
Place *ThemeMaster.sh* and *ThemeMaster* folder in `/opt/tools`

## RetroOZ
Need to be on RetroOZ 0.50 - Beta - 2 July or newer.
Place *ThemeMaster.sh* and *ThemeMaster* folder in `/roms/tools` (or directly in /opt/system/Tools).

# Support ThemeMaster
No better support than ThemeMaster being used! If you have a GitHub account you can show it by starring the project.

Feel free to suggest any enhancement and to report any issue directly through GitHub. Alternatively - and for any questions, comments or feedback - you can find me on the [Retro Game Handhelds](https://discord.gg/wurh4WM) Discord’s server. 
