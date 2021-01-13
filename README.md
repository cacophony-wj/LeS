- [Preamble](#preamble)
	- [A word about ENBs](#a-word-about-enbs)
	- [Requirements](#requirements)
		- [System Specs](#system-specs)
	- [Installation](#installation)
	- [Pre-Installation](#pre-installation)
		- [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
		- [Steam Config](#steam-config)
	- [Using Wabbajack](#using-wabbajack)
	- [Downloading and Installing](#downloading-and-installing)
	- [Problems with Wabbajack](#problems-with-wabbajack)
	- [Post-Installation](#post-installation)
	- [Preparing the Game](#preparing-the-game)
	- [Crafting the Female Bodies](#crafting-the-female-bodies)
	- [Launching the Game](#launching-the-game)
	- [Removing the Modlist](#removing-the-modlist)
	- [Contact](#contact)
	- [Contributing](#contributing)
	- [Changelog](#changelog)


# Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

I'm [cacophony](https://github.com/cacophony-wj), a humble person. I want to provide a slightly lewd modlist friendly to male or female characters that will have enough NSFW mods for a spicy experience but not quite so many that you're no longer unable to enjoy the game of Skyrim. Consider this the "Game of Thrones" version of Skyrim -- a lot of clam and wang -- but not a full on porn parody like most Lover's Lab lists.

Your kinks are a very private thing. As opposed to piling together a modlist for every possible fetish, I have created a fun list for myself with beautiful characters and easy ways to initiate dialog sex with the highest quality and most frequently updated animations. The systems are kept intentionally light to ensure SexLab is as stable as it can be and to allow for greater compatibility with user additions. The patches are individual to each mod and there are no merges, allowing for almost anything to be added or removed.

_Death Alternatives_ don't work reliably. I can't stand it when they fail and I can't stand trying to improve their success rate. I have included _Ashes_ so you can spawn in a separate cell before reloading, as Wabbajack recommends. If you want to take this respawn mod as an opportunity for a "hardcore" playthrough, feel free to do so, but that is not its intention. Just wait until the screen fades in from black and reload.

# A STRONG WARNING

## SexLab SE is still **beta!** It is still buggy!

Before asking a question, look at [Troubleshooting](https://github.com/cacophony-wj/LeS/blob/master/TROUBLESHOOTING.md). Many common questions are answered there.

## A word about ENBs

This list was reborn with the intention of following Rudy's _Cathedral Weathers ENB_ weather and lighting recommendations. However I have grown weary of the incredibly dark interiors and nights. Rudy also hasn't updated through several ENB revisions, so I have swapped things out for _PI-CHO KONAN EDITION_ from those Korean masters. If you don't like it, I have also included the original _Rudy Cathedral_, _Serio's ENB_, _LJoss_, and _PI-CHO Standard_ in the downloads directory which you can install if you wish to try them. If you are running this modlist at 4k, I _strongly_ recommend switching the ENB to _Serio's_. Don't limit yourself to my choices, though, in theory, any _ENB_ that works with _Cathedral Weathers_ will work here, including the popular _Silent Horizons_. Choose carefully, ENBs are the most demanding part of any modlist. 

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)

### System Specs

This portion is under review, but my best estimate as to what you need is as follows:

- CPU: >= 7th gen Intel processor OR >= AMD Ryzen 3000 series processor
- GPU: >= 1070, you need at least 6GB of VRAM
- RAM: >= DDR4 with at least 12GBs

Everything should be installed on an SSD that has at least 250GB of space available. 

Please note that you will also require _at least_ an additional 30GB on the drive you installed Wabbajack.exe to for extraction and recompression of files.

## Installation

##  Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to **Updating**  in the **Troubleshooting** section.

###  Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017 and 2019". <a href="https://aka.ms/vs/16/release/vc_redist.x64.exe">Direct link</a> if you can't find it.

###  Steam Config

**Change Steam's Update Behavior**

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you and lock you out of playing your _Wabbajack_ modlist(s), head over to the Properties window, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_ while you're at it.

**Set the Game language to English**

Wabbajack will check your game files and make sure that we have the same version. This also means that any other language than English will fail the installation.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

**Install Skyrim** (OPTIONAL)

If Skyrim is not installed, do so. _DO NOT_ install it _ANYWHERE_ inside a _Program Files_ folder. This will only wreak havoc in the end. 

If you must, create a Steam library elsewhere on your computer (for example, _D:\Steam_) and install Skyrim there. (Options for such are given within Steam.)

If you only have one hard drive and Steam is installed to _C:\Program Files_, you will have to relocate it to _C:\_. I'm sorry.

**Clean Skyrim**

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. **Do not install Skyrim anywhere inside any Program Files folder. Wabbajack will not work in a folder that is protected by Windows.** You should also clean up the Skyrim Special Edition folder in Documents/My Games/. If you have download throttles or caps, or just don't want to wait, you can also use [Skyrim Shredder](https://www.nexusmods.com/skyrimspecialedition/mods/30133) by trawz to clean your installation.

**Start Skyrim**

After you have done everything above and have a clean SSE installation ready, start the Launcher and open the Options menu.

    Click on Ultra
    Set the Aspect Ratio and Resolution to your monitor's native values
    Set Antialiasing to Off
    Uncheck Windowed Mode and Borderless

Start the game and exit once you're in the main menu.

##  Using Wabbajack

##  Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. You will also need an additional 30 GB beyond the modlists' official size to store temporary working files. It is not recommended to allow your drive to get over 90% full (red bar in File Explorer) so be sure to leave yourself a little headroom on top of all that.

    Adjust the Installation Location to a directory located on the root directory of one of your drives
    For example, this might be "C:\Licentia", "D:\Licentia", or "E:\Licentia"
    Ensure the Download Location is within that directory
    Click the Go/Begin button
    Wait for Wabbajack to finish

##  Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**DO NOT CONTACT MOD AUTHORS DIRECTLY.**

I, cacophony, fully accept any responsibility for difficulties with this list and any conflicts I introduce, so please do not question mod authors on the _Nexus_, _Lover's Lab_, _Vector Plexus_ or any other site about bugs that may result from this lists' use. Direct your questions to me, not the innocent mod authors who should never be expected to support a modlist setup.

**Could not download x:**

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till the modlist receives an update.

**x is not a whitelisted download:**

This can happen when update the modlist receives an update. Check if a new update to the modlist is available and wait if there is none.

**Wabbajack could not find my game folder:**

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the Pre-Installation step. If this still doesn't work, ensure that you are not running Wabbajack as an Administrator.

**All downloads from Lover's Lab are failing.**

Lover's Lab is much more restrictive about automated downloads to users outside of the United States. Attempt to use a free- or budget- VPN with a terminus in the United States to automate your downloads. If you do not have such an option, you will need to download the LL mods manually, as per the manifest section below.

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple Wabbajack lists. Sometimes it does anyway. Try signing up for a MEGA account, or if you have already done so, try logging out of it and downloading anonymously (although much more slowly). I can't tell you to do it, but a VPN _has been known_ to circumvent some of **MEGA**'s restrictions.

**Downloading from the Manifest**

Sometimes no matter what anyone tries, a file will not download from Wabbajack for some reason. If that happens to you, go to the _www.wabbajack.org_ website, find the gallery entry for _Licentia_, click _Archive Search_ and type _the filename_ of each mod you cannot download automatically. They can be downloaded from the _link_ icon (looks like a chain link). Ensure that any files you download go to your _Licentia_ downloads directory. Just save them there, do _not_ open them and definitely do _not_ extract them. Close Wabbajack, reopen it, and click the **PLAY** button again.

**Wabbajack cannot continue because of unknown files.**

Move your downloads folder outside of your _Licentia Directory_, ensure the _Licentia Directory_ is clear of all files, then close and restart Wabbajack. Be sure to point the downloads box to your relocated downloads folder.

## Post-Installation

**Copy Game Folder Files**

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and extract _only_ d3d11.dll and d3dcompiler_46e.dll from the _WrapperVersion_ folder to your game folder. This is the directory in which _SkyrimSE.exe_ is located.

Copy all of the files located inside the _Licentia Directory/game folder files_ directory to your game folder.

Please note, **do not copy the entire game folder files folder.** Only copy the files _inside_ that folder to _Steam/steamapps/common/Skyrim Special Edition_. There should be around 10 of them, as well as a folder entitled "enbseries".

## Preparing the Game

The next step is to prepare the game for play. Navigate to the directory where you installed the modlist _Licentia_. Inside you will notice an executable file called _ModOrganizer.exe_. This file (the _Mod Organizer 2_ application) has already been automatically installed and configured by Wabbajack with all the necessary mods to run the modlist and does not need to be updated, replaced, or manually configured. Simply launch it to continue.

## Crafting the Female Bodies

Unfortunately I don't feel comfortable offering precompiled BodySlide outputs because this essentially rehosts all of a 3D modelers' work in another location. So you will have to build them yourself. Please don't abandon me here, I've minimized the steps as much as possible. There are only four options you really have to choose from and they're all hair colors, it's pretty much an autopilot procedure. Check out the document below.

[Female Bodies and Outfits](https://github.com/cacophony-wj/LeS/blob/master/BODYSLIDE.md)

## Launching the Game

The rest must be completed after the game itself is launched. I recommend bringing up this readme on a portable device by navigating to [www.wabbajack.org](https://www.wabbajack.org) and referring to the Gallery. Anyway, Launch the modlist from the command which reads **SKSE (RUN ME TO START THE GAME)**. If you receive a message that files are missing, do not exist, or a warning about an incorrect path, you _may_ have to edit the link to "skse_loader" in the drop down and point it to your Skyrim directory. Once you are in-game, create your character and follow _all_ of the instructions in the below link:

[Licentia Configuration](https://github.com/cacophony-wj/LeS/blob/master/MCMs.MD)

## Removing the Modlist

You can just remove the _Licentia_ folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Contact

I am regularly available on the [Wabbajack Discord](https://discord.gg/wabbajack) (`#nsfw-mod-discussion`) (`#licentia-support`). I will not respond to direct messages unless I know you. **DO NOT DIRECT MESSAGE ME**

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
