# Happy-fun-times

- [Introduction](#Introduction)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
      - [Disable the Steam Overlay](#disable-the-steam-overlay)
    - [Change Steams Update Behavior](#change-steams-update-behavior)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading and Installing](#downloading-and-installing)
      - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
- [Updating](#updating)
- [Gameplay Guide](#gameplay-guide)
- [In-Game MCM Options](#in-game-mcm-options)
- [FAQ](#faq)
- [Removing the Modlist](#removing-the-modlist)
- [Credits and Thanks](#credits-and-thanks)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Introduction

Happy Fun Times is a nsfw modlist built around my attempts to create consistent random and dynamic encounters. HFT's nsfw content is based around the [toys family of mods](https://virginmarie1.wixsite.com/toys) which generally favor moderately intrusive mechanics and consensual encounters. HFT features drastically changed enemies, perks and leveling, legacy of the dragonborn, and "modern" combat. 

THE PAID ANNIVERSARY EDITION UPGRADE IS REQUIRED. THIS LIST WILL NOT INSTALL WITHOUT IT.

Support is only available in the [Jolly Co-Operators](https://discord.gg/jolly-coop)


## Installation

#### Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019". [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

#### Steam Config

#### Set the Game language to English

You must do this for wabbajack to work. If your game was previously set to non-english make sure to verify your files on steam after fixing it. There is no support for non-english skyrim.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

### Using Wabbajack

#### Preparations

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in X:\Wabbajack

#### Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. You can have the HFT and downloads folder be on separate drives without issue, aside from being limited by the slowest drive during wabbajack installation.

1. Open Wabbajack
2. Load the Modlist from Disk
3. Set TSO to install to X:\Happy Fun Times and download to X:\Happy Fun Times\Downloads. Your downloads folder can be on a separate drive to save space but wabbajack's install speed will be limited to your slowest drive. 
4. Click the Go/Begin button
5. Wait for Wabbajack to finish

##### Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. If you do not see an installation failed warning do not worry about it. If you feel like wabbajack is stuck or a download is hanging just restart wabbajack, it will pick up from exactly where you left off.  Please rerun wabbajack at least twice and try to manually download the file from nexus/ll first before posting about a failed download.

**Could not download x**:

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till I update the Modlist.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Post-Installation

#### Starting the Game

Head over to the installation folder and locate an executable named ModOrganizer.exe and launch it. Once its launched there will be a dropdown box on the top right and a big run button next to it. Ensure it is set to SKSE by selecting it in the dropdown box and then hitting the run button.

## Updating

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

# Gameplay Guide



## Vorkiinator Black

HFT uses Vorkiinator Black which is a splice of Vokrii, Ordinator, Path of Sorcery, Adamant and SPERG. It has an absolutely insanely number of perks. Using [this perk calculator](https://thehajo.github.io/VokriinatorBlack/) will help in planning a build. If you don't feel like planning it should be somewhat difficult to make a truly useless build considering the general power level of perks available.

## Static Skill Leveling

HFT uses [Static Skill Leveling](https://www.nexusmods.com/skyrimspecialedition/mods/30410) to change how skill leveling works. Gone are the days of crafting hundreds of iron daggers to level up smithing, now you get to pick exactly what skills you want to level up on the level up screen. Make sure to level skills BEFORE picking your attribute as picking an attribute closes the skill selection screen until your next level up. If you have excess unspent skill points SSL will save them for the next time you level up, but you can only level up each skill by 5 per level up. 

The rates of experience and skill points are still being fined tuned. 

## Toys and Addons
 
[Toys](https://virginmarie1.wixsite.com/toys) is a pretty well put together suite of mods that plays quite differently from most Sexlab based mods. I suggest reading through the Toys site to understand how each of its main mods work, or reading the ingame guidance that comes up as you play. Remember that the rates can be tweaked in the MCM so you can play a character that struggles to ever wear anything that isn't a toy or almost entirely ignore the NSFW mechanics depending on what settings you choose. Your MCM settings will be auto-saved for new characters until you update the modlist or re-run wabbajack.

## Enemy Mods

HFT has a slew of enemy mods, including a cleaned version of Rogue-like Ecnounters, Heritage, Heritage 2, OBIS, Skyrim Immersive Creatures, SRCEO, and Enemy Variations Wenches. No encounter will ever quite feel like vanilla and there will be sudden random difficulty spikes. If you find yourself in over your head running away is always a valid choice.

Dragons have been changed as well, good luck.

## Modern Combat

HFT uses MCO ADXP as its "modern" combat mod along with Precision, SCAR, TK Dodge RE, and Valhalla Combat. Melee combat is really strong once you figure out the system. 

## Character Customization

HFT has two MCMs related to character customization that are easy to miss. Racemenu animated overlays will allow you to determine when overlays appear during combat. Skyrim outfit system allows you to set visual only outfits for various situations and locations. It's effectively transmog in skyrim, finally.

Skyrim outfit system has a setting to require an item equipped in the displayed slot if you wish to ensure stripping compatability from Toys and Love.

## In-Game MCM Options

All MCM options have been preconfigured.

## FAQ

SKSE instantly crashes when I try to start the game
- Please ensure you have .NET v5.0 installed. Download and install both Console Apps x64 AND Desktop Apps x64 versions from Microsoft:
https://dotnet.microsoft.com/download/dotnet/5.0/runtime

I'm playing on a resolution above 1080p and my game resolution is messed up when I start the game!
- First, open up MO2, open up MO2's ini editor, and make sure the resolution in the skyrimprefs ini **in mo2** is set to the correct resolution. If this does not solve your problem open up SSE Display Tweaks in mo2, open up its ini and edit it to fit your resolution or just turn it to fullscreen. Finally if you still have a problem check windows scaling settings for skyrim.

Why is there a lantern always attached to my character?  Why am I always casting light?
- This is provided by a mod called quick light.  Holding E will toggle a light on and off to help brighten darker areas

How do I update to a later version?
- All you have to do is rerun wabbajack with the new version of the installer. If you have the downloads wabbajack will hash everything, download any new mods, and make the necessary changes in your install folder. You do not need to recopy the game folder files unless they have changed.

My character's hair/eyebrows/beard has weird texture issues
- You need to use High Poly Head and non-vanilla hair/eyebrows/beard (HPH has duplicates made for HPH)

How do I use High Poly Head?
- In racemenu search for “face part” and move the slider. HPH will work on any pre existing presets that you have, but you will need to use HPH's eyebrows.

Loverslab downloads keep failing!
- First make sure you verified your LL account and then restart WJ. If that doesn't work log in and out of LL in the WJ UI. If that doesn't work, grab the failing links from the WJ log, download the files manually, and put them in your downloads folder.

How do I set skyrim to borderless windowed mode?
- It should already be in borderless windowed mode. But if for some reason it isn't change the settings in the SSE Display Tweaks INI in MO2.

I have an ultrawide monitor (21:9), how do I fix the aspect ratios?
- Install the following mods: Complete Widescreen Fix, Extended UI - Widescreen fix, Wider MCM menu for Skyui Widescreen Fix, SkyUI SE - Flashing Savegames fix - Widescreen Fix, Better MessageBox Controls Widescreen fix, Better Dialogue Control Widescreenfix

I have an 60+ Hz screen (100hz, 144hz). What should I do?
- Edit the SSE Display Tweaks ini to properly support your monitor.

Is [insert mod name here] part of the list?
- Check the modlist manifest. If there is something you want that is not in the list, I highly suggest you do not add it unless you know what you’re doing.

Will you add x mod to the list?
- It's extremely unlikely unless its already on my radar.

Are you going to add a bunch of armor mods like TSO?
- Working on it slowly.

I think I found a bug! Here are some things that are not bugs:
- None yet, thankfully.

## Performance

My Setup:

- Ryzen 5600x
- RTX 3080 Ti
- 32GB DDR4
- Game and MO2 running on a m2 drive

I get a consistent 60+ fps in game at 1440p. If you get bad frames I suggset not wearing as SMP items. NAT ENB has a preformance setting on its nexus page, try applying that as well, trying to disable the ENB will render the game rather unplayable without also changing the weather. I don't provide support for making your fps better so please do not ask me. N

## Removing the Modlist

You can just remove the MO2 folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Credits and Thanks

Thank you to Phoenix and crew for The Phoenix Flavor which served as a visual base of this list. HFT is forked from Phoenix Flavor v4, if you want an even better looking list I suggest you try Phoenix Flavor v5, Phoenix put some real effort into making it look great and run well. 

Special Thanks
- Erri for the base of the readme that was forked into elder souls from which this readme is forked
- The Wabbajack Team - For enduring months of hearing about this list before it was released

Mod Authors
- And of course, where would we be without Skyrim’s awesome mod authors? Thank you all for releasing the quality content that you guys do. PLEASE DO NOT FORGET TO ENDORSE THE AUTHORS!

## Contact

While I'm always available on the [Requiem Wabbajack Discord](https://discord.gg/WCbdB9TYbj), I would advise checking the [Issues](https://github.com/NotTotal/Total-Skyrim-Overhaul/issues) (open **and** closed ones) on GitHub first if you have any problems. **DO NOT DM ME ON DISCORD. I WILL NOT PROVIDE SUPPORT FOR YOU IN DMS**.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
