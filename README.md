# Fresh-Install-Windows-Setup-Guide
This guide is intended to help setup a fresh install of Windows. Basically a personal checklist but I will make it public so that other people can benefit from it as well. I will look at Pull requests. If you don't explain why your addition is better then I will most likely ignore it.

# Obtain Windows to install
- Use [Windows Media Creation Tool](https://go.microsoft.com/fwlink/?LinkId=691209) to get the latest iso straight from Microsoft and install it straight to your flashdrive.

# Updates
## Motherboard BIOS and Driver Updates
You should do this before anything else on your computer! BIOS first, but those can even be done before you reinstall Windows. The rest will be things like chipset drivers, on-board audio drivers, and LAN drivers. You don't have to install everything but if you are uncertain about a specific driver look it up.
- Find your Motherboard Make and model and search for that plus 'drivers'. For example, with the motherboard 'ASRock X570 Steel Legend' you will search for 'ASRock X570 Steel Legend drivers' and look for a page owned by the manufacturer. Look for a 'support', 'drivers', 'bios and firmware' or something of the sort. For the above example the page would be this: https://rog.asus.com/motherboards/rog-strix/rog-strix-x570-e-gaming-model/helpdesk_bios

## Windows Updates
- [Windows] + [I] > Update & Security > Check for Updates
-  If your installation media was too far behind (If you used the 'Obtain Windows to install' section above it wont be.), updates can take a while. A good solution is to use [Windows Update Assistant](https://www.microsoft.com/en-us/software-download/windows10) to update your computer. After you do it this way do the method above to make sure there are no smaller updates that need to be added.

## Driver Updates
The above updates should get most of your drivers but for some things you will want to grab the drivers from the manufacturer because Windows Update wont have the latest of some of them.
### Graphics Cards
- Nvidia
  - [Nvidia Geforce Experience](https://www.nvidia.com/en-us/geforce/geforce-experience/)
  - [NVCleanstall](https://www.techpowerup.com/download/techpowerup-nvcleanstall/): Watch a video about this [here](https://www.youtube.com/watch?v=LR1XkjtylCM).
- AMD
  - [AMD Radeon Software](https://www.amd.com/en/technologies/radeon-software)

# Software Installs
## General Software
- [ninite](https://ninite.com/): This will help you install many of the most important softwares.
  - [Basic (non-gamer) config](https://ninite.com/7zip-chrome-firefox-revo-teracopy/).
  - [My personal config](https://ninite.com/.net4.8-7zip-adoptjavax8-chrome-discord-firefox-googlebackupandsync-greenshot-pythonx3-revo-spotify-steam-teracopy-vlc-winscp-xnview/) (I recommend making your own with the first link)
- [VS Code](https://code.visualstudio.com/download) I do not install this from ninite because it doesn't give the option to add to the context menu. Meaning that you can't right click a file and select "open with Code" which is helpful for looking at files of many types.

## Gaming Software
- Install all of the game launchers that you use:
  - [Steam](https://store.steampowered.com/about/) (I install this with ninite above)
  - [GOG Galaxy](https://www.gog.com/galaxy)
  - [Battle.net](https://www.blizzard.com/en-us/apps/battle.net/desktop)
  - [Ubisoft Connect](https://ubisoftconnect.com/en-US/) (Formerly Uplay)
  - [Origin](https://www.origin.com/usa/en-us/store/download)
  - [Epic Games](https://www.epicgames.com/store/en-US/download) (I don't grab this one but I figured I'd include it)
 
## Programming Software
- [Visual Studio](https://visualstudio.microsoft.com/downloads/)

# Gaming Specific
- [Turn off](https://www.tomshardware.com/news/how-to-disable-mouse-acceleration-windows,36886.html) Mouse Acceleration. [Why](https://prosettings.net/library/what-is-mouse-acceleration/)?
- [Change](https://support.microsoft.com/en-us/windows/change-your-display-refresh-rate-in-windows-c8ea729e-0678-015c-c415-f806f04aae5a) your refresh rate. (If you have a monitor with a higher refresh rate than 60Hz)
