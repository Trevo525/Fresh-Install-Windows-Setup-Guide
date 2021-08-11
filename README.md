# Windows Fresh Install Setup Guide
This guide is intended to help setup a fresh install of Windows. Basically a personal checklist but I will make it public so that other people can benefit from it as well. I will look at Pull requests. If you don't explain why your addition is better then I will most likely ignore it.

**Note**: Any article linked in this guide will be followed by [[A](https://web.archive.org/)]. This is an Archive.org link through their [Wayback Machine](https://web.archive.org/) service. This allows me to save the exact state of the article. If any links are broken, the [[A](https://web.archive.org/)] can be used to see what I saw at the time of adding the article to this guide. I would still use the normal links first and keep the archive as a backup.

# Obtain Windows to install
This guide is not intended to walk you through the install process. I included this as it might be helpful but I'm not going to make a guide on the install process since it's been covered many times in other guides.
- Use [Windows Media Creation Tool](https://go.microsoft.com/fwlink/?LinkId=691209) to get the latest iso straight from Microsoft and install it straight to your flashdrive.

# Updates
Even (especially) a fresh install of Windows will require updates. I suggest you follow the order of this guide and install these from top to bottom as they appear.
## Motherboard BIOS and Driver Updates
You should do this before anything else on your computer! BIOS first, but those can even be done before you reinstall Windows. The rest will be things like chipset drivers, on-board audio drivers, and LAN drivers. You don't have to install everything but if you are uncertain about a specific driver look it up.
- Find your Motherboard Make and model and search for that plus 'drivers'. For example, with the motherboard 'ASRock X570 Steel Legend' you will search for 'ASRock X570 Steel Legend drivers' and look for a page owned by the manufacturer. Look for a 'support', 'drivers', 'bios and firmware' or something of the sort. For the above example the page would be this: https://www.asrock.com/mb/AMD/X570%20Steel%20Legend/#Download

## Windows Updates
- [Windows] + [I] > Update & Security > Check for Updates
-  If your installation media was too far behind (If you used the 'Obtain Windows to install' section above it wont be.), updates can take a while. A good solution is to use [Windows Update Assistant](https://www.microsoft.com/en-us/software-download/windows10) to update your computer. After you do it this way do the method above to make sure there are no smaller updates that need to be added.

## Driver Updates
The above updates should get most of your drivers but for some things you will want to grab the drivers from the manufacturer because Windows Update wont have the latest of some of them.
### Graphics Cards
- **Nvidia**
  - [Nvidia Geforce Experience](https://www.nvidia.com/en-us/geforce/geforce-experience/)
  - [NVCleanstall](https://www.techpowerup.com/download/techpowerup-nvcleanstall/): Watch a video about this [here](https://www.youtube.com/watch?v=LR1XkjtylCM).
- **AMD**
  - [AMD Radeon Software](https://www.amd.com/en/technologies/radeon-software)
### Peripherals
There is no way for me to know what peripherals you use. Here I will make a list of peripherals to think about and you can look their drivers up specifically. For gaming this is recommended to get the most performance out of each device. But if you have a cheap device or don't need the nicest polling rate on your mouse, for instance, you can ignore these.
- **Mouse**: I would suggest getting the best drivers for a mouse, there are many things that it can help but if you play First Person Shooters then this can be really important!
- **Keyboard**: This is mostly going to help with RGB or other features that your keyboard might have.
- **Monitor**: This might not really be necessary or even really a "driver" but like to download the color profiles for my main monitor and install them to make sure the colors *hopefully* the best that they can be.
- **Headset/Headphone/Microphone**: I have headphones and a microphone, so I would look up the drivers separately. If you have a headset (headphones with built-in microphone) you will only have to look up drivers for the one. I highly recommend making sure you look up drivers here! Sound quality is one of the most important things in gaming.
- **Other**: There are so many things I can list here but it really comes down to each person and what you have plugged in. Basically, think about each USB that is plugged in and each PCI device on the motherboard and whether they stand to have any benefits of having the latest drivers. Here is a sample list of things that one might want to look for: Optical Disk Drive, Webcam, RGB Controller, StreamDeck, etc.

# Software Installs
This is highly subjective. I categorized it into three sections: General, Gaming, and Programming software. If you don't program, don't install from that section. If you don't play games, don't install from that section.
## General
- [**ninite**](https://ninite.com/): This will help you install many of the most important softwares.
  - [**Basic (non-gamer) config**](https://ninite.com/7zip-chrome-firefox-revo-teracopy/).
  - [**My personal config**](https://ninite.com/.net4.8-7zip-adoptjavax8-chrome-discord-firefox-googlebackupandsync-greenshot-pythonx3-revo-spotify-steam-teracopy-vlc-winscp-xnview/) (I recommend making your own with the first link)
- [**VS Code**](https://code.visualstudio.com/download) I do not install this from ninite because it doesn't give the option to add to the context menu. Meaning that you can't right click a file and select "open with Code" which is helpful for looking at files of many types.

## Gaming
- Install all of the game launchers that you use:
  - [**Steam**](https://store.steampowered.com/about/) (I install this with ninite above)
  - [**GOG Galaxy**](https://www.gog.com/galaxy)
  - [**Battle.net**](https://www.blizzard.com/en-us/apps/battle.net/desktop)
  - [**Ubisoft Connect**](https://ubisoftconnect.com/en-US/) (Formerly Uplay)
  - [**Origin**](https://www.origin.com/usa/en-us/store/download)
  - [**Epic Games**](https://www.epicgames.com/store/en-US/download) (I don't grab this one but I figured I'd include it)
 
## Programming
- [**Visual Studio**](https://visualstudio.microsoft.com/downloads/)
- [**WSL2**](https://www.sitepoint.com/wsl2/) [[A](https://web.archive.org/web/20210811145613/https://www.sitepoint.com/wsl2/)] (Windows Subsystem for Linux 2)

# Windows Configurations
These configurations are things that I've had written down to remember each time but can be very important for gaming. I might add more categories later on but for now I only have important Gaming configs that I find myself doing often.
## Gaming
These are very important to remember for most gamers. 
- [Turn off](https://www.howtogeek.com/740365/how-to-turn-off-mouse-acceleration-on-windows-10/) [[A](https://web.archive.org/web/20210729023311/https://www.howtogeek.com/740365/how-to-turn-off-mouse-acceleration-on-windows-10/)] Mouse Acceleration. [Why](https://prosettings.net/library/what-is-mouse-acceleration/)? [[A](https://web.archive.org/web/20210125100220/https://prosettings.net/library/what-is-mouse-acceleration/)]
- [Change](https://support.microsoft.com/en-us/windows/change-your-display-refresh-rate-in-windows-c8ea729e-0678-015c-c415-f806f04aae5a) [[A](https://web.archive.org/web/20210709161535/https://support.microsoft.com/en-us/windows/change-your-display-refresh-rate-in-windows-c8ea729e-0678-015c-c415-f806f04aae5a)] your refresh rate. (If you have a monitor with a higher refresh rate than 60Hz)
