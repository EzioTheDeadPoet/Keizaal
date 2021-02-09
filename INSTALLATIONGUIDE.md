# Installation Guide

Current version: 02/08/2021 4.0.2.4

![total-installs](https://img.shields.io/endpoint?label=Total%20Installs&style=for-the-badge&url=https://build.wabbajack.org/metrics/badge/keizaal/total_installs_badge.json)  
![build-status](https://img.shields.io/endpoint?label=List%20Status&style=for-the-badge&url=https://build.wabbajack.org/lists/status/keizaal/badge.json)

# What is Keizaal?

Keizaal is a simple modlist that seeks to enhance and expand on Skyrim without compromising Bethesda’s original vision that we all fell in love with back in 2011.  

1.  This modlist is lite and intends to maintain the Vanilla feel. A lot of the time modlists can become ridiculously huge and bloated, but this modlist wants to be nice and lean. Less is more. 
2.  Immersion is paramount. I'm a lore buff and immersion is very important to me. If a mod is not lore accurate or takes me out of the game in any way it will be excluded. Consistency also falls into this category, if a mod has a completely different aesthetic from Vanilla or any of my other mods then it will probably not be included.
3.  Mods must have decent longevity. This modlist wants to be somewhat relevant, in theory, forever.
4.  Stability is the most important thing. This rule basically supersedes all the above. If a mod introduces major stability concerns it will be quickly cut.

You can find a full list of the mods included in Keizaal [here](https://modwat.ch/u/Keizaal/){:target="_blank" rel="noopener"}. If you're still curious about what exactly Keizaal has in store for you, have a look at the overview [here](https://pierredespereaux.github.io/Keizaal/).

# Table of Contents
- [Setup and Information](#setup-and-information)
  - [Clean Install](#clean-install)
- [Keizaal Installation](#keizaal-installation)
  - [Copying the Game Folder Files](#copying-the-game-folder-files)
- [Playing Keizaal](#playing-keizaal)
  - [Mod Configuration](#mod-configuration)
- [Additional Configuration (Optional)](#additional-configuration-optional)
  - [Switching the ENB](#switching-the-enb)
  - [Optional Mods](#optional-mods)
  - [Mod Notes](#mod-notes)
  - [BethINI](#bethini)
- [Updating](#updating)
  - [Semantic Versioning](#semantic-versioning)
- [Troubleshooting](#troubleshooting)
  - ["Wabbajack throws an error after authorizing through Nexus."](#wabbajack-throws-an-error-after-authorizing-through-nexus)
  - ["A mod fails to download."](#a-mod-fails-to-download)
  - ["ModOrganizer.exe throws and error when trying to launch."](#modorganizerexe-throws-and-error-when-trying-to-launch)
  - ["The NPCs during the Helgen intro are just standing in place."](#the-npcs-during-the-helgen-intro-are-just-standing-in-place)
  - ["Skyrim is capped at 72 FPS."](#skyrim-is-capped-at-72-fps)
  - ["Skyrim is acting strangely after automatically sorting the load order."](#skyrim-is-acting-strangely-after-automatically-sorting-the-load-order)
  - ["Tweaks made with BethINI aren't correctly changing the settings in-game."](#tweaks-made-with-bethini-arent-correctly-changing-the-settings-in-game)
  - ["Manual .ini tweaks aren't correctly changing the settings in-game."](#manual-ini-tweaks-arent-correctly-changing-the-settings-in-game)
- [Credits](#credits)

## Setup and Information

Keizaal takes up 188GB of hard drive space (114GB installation with 74GB of downloads) and will likely take a few hours to download depending on your internet speed. It is recommended that you install it on a solid state drive for optimal performance, but a standard hard disk drive will suffice. This modlist was developed on a computer running [these specs](https://pcpartpicker.com/list/3ygt4d){:target="_blank" rel="noopener"}, on this system a stable and consistent 50 - 60 FPS is the norm. Your mileage may vary, there is nothing I can do if you experience poor performance.

Install the latest version of Wabbajack from its [GitHub page](https://www.github.com/wabbajack-tools/wabbajack/releases/latest){:target="_blank" rel="noopener"}.

Create a new folder called “Wabbajack” in the root of your main drive, the default is (C:). Extract Wabbjack.exe into this folder.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/1.%20Installing%20Wabbajack.png)

### Clean Install

To completely reinstall Skyrim, it is advised that you use the [Skyrim Shredder](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=113028&game_id=1704){:target="_blank" rel="noopener"} tool to completely delete the game. It will remove Skyrim and data related to it, but not the modlist.

Reinstall Skyrim in the root of your main drive, the default is (C:). **It MUST NOT be installed in the Program Files folder**.

Run the Skyrim: Special Edition launcher through Steam and let it detect your settings, then close the launcher. **This is only necessary once**.

## Keizaal Installation

Create a new folder called “Keizaal” in the root of your main drive, the default is (C:).

Open Wabbajack.exe, it should be in the Wabbajack folder in the root of your main drive.

Select the Keizaal modlist from the Wabbajack UI.

Once the installation window opens ensure that the “Installation Location” matches the Keizaal folder you just created (default should be C:\Keizaal\). The download location should populate automatically

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/2.%20Installing%20Keizaal.png)

When you’re ready press the triangular start button.

After starting the installation a window will pop up and ask for you to authorize Wabbajack to use your Nexus account. Log into and authorize Wabbajack on Nexus and the installation will proceed. Wabbajack will now install the modlist, this will take a while so be patient. When Wabbajack is finished, the left panel should say "Installation Complete". At this time it is safe to close Wabbajack.

### Copying the Game Folder Files

Navigate to your Keizaal installation folder (default is C:\Keizaal) and open the “Game Folder Files” folder. This folder contains the list's ENB and all the necessary systems files to ensure Keizaal works properly.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/3.%20Game%20Folder%20Files.png)

Copy everything in it to your Skyrim Special Edition directory (the folder containing SkyrimSE.exe). Keizaal is ready to play!

## Playing Keizaal

Now that Keizaal has been installed you will need to launch Skyrim in a slightly different way.

Navigate back to your Keizaal installation folder and run ModOrganizer.exe.

You should now be on a screen that displays all of your installed mods on the left and all of your plugin files on the right.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/4.%20Playing%20Keizaal.png)

You will now have to launch Skyrim by selecting “Keizaal” from the drop-down menu directly above the right plugins pane and pressing “Play”. Beneath the Play button there is a way to add a Skyrim shortcut to your desktop for added convenience.

### Mod Configuration

All of the Mod Configuration Menus menus and .inis in Keizaal have been pre-configured to my recommended settings. The only thing you need to do when you start a new game is play.

## Additional Configuration (Optional)

This following section outlines some additional, optional confiurations. Nothing here is necessary, but it may be of some interest to users who like to tweak.

### Switching the ENB

Keizaal comes with its own prepackaged ENB preset. If, for whatever reason, you don't want to use this prepackaged preset, I urge you to at least use an ENB that doesn't break imagespace modifiers. I believe any ENB that breaks imagespace modifiers is automatically bad, no matter how pretty it may look.

[ENB and ReShade Manager](https://www.nexusmods.com/Core/Libs/Common/Widgets/DownloadPopUp?id=76937&game_id=1704){:target="_blank" rel="noopener"} is a great tool for easily switching between ENB presets. If you decide against using Keziaal's preset, I recommend this program to easily remove all traces of the preset from your Skyrim directory.

### Optional Mods

There are a handful of mods that I have included that are disabled by default; these mods aren’t part of the main Keizaal package. If you choose to activate an optional mod, be sure to move the mod's plugin (on the right pane of Mod Organizer) **above all** of the plugins with the "Keizaal" prefix unless otherwise instructed in the mod's notes.

I will try to assist you in enabling these optional mods, however if you make changes to Keizaal outside of these few mods I will not be able to help you. Any personal edits you make to this list must be done independently.

### Mod Notes

Several mods in Keizaal's Mod Organizer have notes attached to them. If the note icon appears next to a mod, hover over it to read the notes I've added. These notes will give you some additional context about how I have configured the mod.

Here is an example of one such note:

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/4.%20Playing%20Keizaal.png)

### BethINI

BethINI is a powerful tool that replaces Skyrim's Vanilla launcher settings menu, you can utilize it to tweak the game's settings. In order to use it, select it from the dropdown in the top right-hand corner of Mod Organizer, then start it the same way you'd launch Skyrim. 

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/6.%20BethINI.png)

After you have launched BethINI, be sure to **close Mod Organizer before you change any settings**!

## Updating

If this Modlist receives an update, please check the changelog before doing anything. Always backup your saves or start a new game after updating.

**Wabbajack will delete all files that are not part of the Modlist when updating!**

This means that any additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the overwrite existing Modlist button.

### Semantic Versioning

Keizaal uses semantic versioning in order to quickly determine the size of an update and if it is savegame compatible or not. This is what the version numbers mean:

- <ins>**1**</ins>.0.0 = A large update that is **NOT** savegame compatible and fundamentally changes the list.
- 1.<ins>**1**</ins>.0 = An update that is **NOT** savegame compatible.
- 1.1.<ins>**1**</ins> = An update that **IS** savegame compatible.
- 1.1.1.<ins>**1**</ins> = A small hotfix that **IS** savegame compatible.

You can find your current version of Keizaal at the top of Mod Organizer. If the version isn't listed you're probably using a pre-3.4.0 version.

## Troubleshooting

### "*Wabbajack throws an error after authorizing through Nexus.*"

Download the [.Net Framework 4.8 Runtime](https://go.microsoft.com/fwlink/?LinkId=2085155). Be sure to restart your computer afterward.

### "*A mod fails to download.*"

If Wabbajack fails to download a mod, try downloading them manually. Place these in your downloads folder where the other Wabbajack downloads are. Do not extract them. Note that some of these are big files and may take a while.

- [Bearnado Markarth Mashup](https://drive.google.com/u/0/uc?export=download&confirm=Jziu&id=1D139AzjXYuiTMjboFa_gmT3mXrmsR0zG){:target="_blank" rel="noopener"}
- [Keizaal Resources](https://github.com/PierreDespereaux/Keizaal/releases/download/4.0.1/Keizaal.Resources.7z)
- Skyrim Realistic Overhaul
  - [Part One](https://www.moddb.com/downloads/start/116891?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
  - [Part Two](https://www.moddb.com/downloads/start/116927?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
  - [Part Three](https://www.moddb.com/downloads/start/116934?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
  - [1.8 Update](https://www.moddb.com/downloads/start/139489?referer=https%3A%2F%2Fwww.moddb.com%2Fmods%2Fskyrim-realistic-overhaul%2Fdownloads){:target="_blank" rel="noopener"}
- [WiZkiD Candle Flames](https://drive.google.com/uc?export=download&id=1ZA8r-McnBcxjCdUBnA4wRW1jZzhHciO2)
- [WiZkiD DynDOLOD Bright Waterfalls Meshes Fix](https://drive.google.com/uc?export=download&id=1g54xGhVezDVOEGjOIoXowSG0XbKeGu57)
- [WiZkiD DynDOLOD Ultra Detailed Ships LOD](https://drive.google.com/uc?export=download&id=1g54xGhVezDVOEGjOIoXowSG0XbKeGu57)
- [WiZkiD Grass and Landscape](https://drive.google.com/u/0/uc?export=download&confirm=qk9_&id=18rmerskUeBZecsdeU_QRpG1QXrIylyA9){:target="_blank" rel="noopener"}
- [WiZkiD Sky Textures](https://drive.google.com/u/0/uc?export=download&confirm=XM-E&id=1lsg11a3blf825KVZsKaevKB5-khmaP9l){:target="_blank" rel="noopener"}
- [WiZkiD Storm Lighting Improved Thunder Sounds](https://drive.google.com/u/0/uc?export=download&confirm=VB0Q&id=1Fg-w1TQgC7WIYOSsOXNFd02egFgn6u3R){:target="_blank" rel="noopener"}
- [WiZkiD Tree Selection](https://drive.google.com/u/0/uc?export=download&confirm=MIlo&id=1BhxtOpeaEHEkli6QKLrhi1bQyNYIdgXG){:target="_blank" rel="noopener"}
- [WiZkiD Unique Flowers and Plants](https://drive.google.com/uc?export=download&id=1MPW2y4cjL31B2Oncx1OMeuTITartQ4q-)
- [WiZkiD Variety](https://drive.google.com/u/0/uc?export=download&confirm=l4nJ&id=1g5yCvLG0Fw-WvPOzEDNMaqBdTwT6eg65){:target="_blank" rel="noopener"}
- [WiZkiD Water Wells with Real Water](https://drive.google.com/uc?export=download&id=1wnWsbLND5rxgJV-keeJG4Ev33XkROugI)

### "*ModOrganizer.exe throws and error when trying to launch.*"

Download the newest [Visual C++ 2019 redists](https://aka.ms/vs/16/release/vc_redist.x64.exe). Be sure to restart your computer afterward.

### "*The NPCs during the Helgen intro are just standing in place*."
 
Make sure you correctly copied the Game Folder Files over to your Skyrim directory.

Please refer to [this section](#copying-the-game-folder-files) for information on how to do so.

### "*Skyrim is capped at 72 FPS.*"

The mod Movement Behavior Overhaul will cause animations to break if the framerate goes over 75 FPS, so I've capped the FPS to 72 in order to prevent that.

### "*Skyrim is acting strangely after automatically sorting the load order.*"

**NEVER USE LOOT OR MOD ORGANIZER TO AUTOMATICALLY SORT YOUR LOAD ORDER!** Keizaal's plugins have been carefully sorted manually in order to ensure that everything works as intended. Sorting the load order using an automatic tool **will** cause issues. If you have used an automated program to sort your load order, you forfeit all support I would normally provide until you restore your load order to Keizaal's default. You should be able to restore your load order to default by rerunning Wabbajack.

### "*Tweaks made with BethINI aren't correctly changing the settings in-game.*"

BethINI can handle the majority of tweaks that you would generally want to make. However, some of the more niche settings may be handled by .inis that BethINI can't edit. These will need to be edited manually.

### "*Manual .ini tweaks aren't correctly changing the settings in-game.*"

For ease-of-use I have placed all the custom .inis for every mod in Keizaal within a mod called "Keizaal Settings" at the bottom of Mod Organizer.

![](https://raw.githubusercontent.com/PierreDespereaux/Keizaal/main/assets/images/installation%20guide/7.%20Keizaal%20Settings.png)

______________________________________________________________________________________________________________________________________________________________________


Contact Pierre Despereaux on either the [Wabbajack](https://discordapp.com/invite/wabbajack){:target="_blank" rel="noopener"} or [Keizaal](https://discord.gg/eYZJFP8){:target="_blank" rel="noopener"} Discord server for individual help and guidance. If you make modifications to Keizaal, you do so at your own risk. No support will be provided.

Please note that manual installations are **NOT SUPPORTED**. There are simply too many variables that go on during manual installations that attempting to troubleshoot each user individually is simply not realistic, it would likely be a waste of everyone's time.

## Credits

**VictorF** for his constant support and helpful criticism regarding both Keizaal and my own mods

**Simon Magus** for tolerating my constant badgering about my load order

**Paleo the Parrot** and **ElectricSparx** for helping me understand xEdit

**Shade088** for all his help getting Keizaal’s graphical suite operational

**Catir** for Keizaal's beautiful banner and icons

**Total**,  **Lively**, and **Double Dog** for helping me get the Wabbajack installer operational over several long nights

**uggcaveman** for saving Keizaal that one time

**Dylan James** for helping me understand what I wanted out of this modlist

**halgari** and entire **Wabbajack Team** for creating such a fantastic resource

The wonderful **mod authors** for making this modlist possible
