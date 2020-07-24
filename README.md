# Licentia et Servitium

![Status](https://img.shields.io/endpoint?url=https://build.wabbajack.org/lists/status/LeS/badge.json)
![Installs](https://img.shields.io/endpoint?url=https://build.wabbajack.org/metrics/badge/LeS/total_installs_badge.json)

- [Licentia et Servitium](#licentia-et-servitium)
- [Licentia et Servitium: A Modest Sampling of Lover's Lab](#licentia-et-servitium-a-modest-sampling-of-lovers-lab)
	- [BEFORE YOU CONTINUE:](#before-you-continue)
	- [Preamble](#preamble)
	- [A STRONG WARNING](#a-strong-warning)
	- [SexLab SE is still **beta!** It is still buggy!](#sexlab-se-is-still-beta-it-is-still-buggy)
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
	- [To Launch the Game](#to-launch-the-game)
	- [Updating](#updating)
- [Number One Rule: This List Is Customizable](#number-one-rule-this-list-is-customizable)
- [Misaligned Animations](#misaligned-animations)
- [Admiring Yourself](#admiring-yourself)
- [A Bit of a Note about "Combat Surrender"](#a-bit-of-a-note-about-combat-surrender)
- [Arousal and CLockwork](#arousal-and-clockwork)
- [A word about ENBs](#a-word-about-enbs)
- [Crafting the Female Bodies](#crafting-the-female-bodies)
- [Game Settings - System and MCM](#game-settings---system-and-mcm)
- [Adding Followers, Outfits, and Other Mods](#adding-followers-outfits-and-other-mods)
- [Removing the Modlist](#removing-the-modlist)
- [Contact](#contact)
- [Contributing](#contributing)
- [Changelog](#changelog)

# Licentia et Servitium: A Modest Sampling of Lover's Lab

## BEFORE YOU CONTINUE: 

The **Github** version is the most up to date. Get the **3.0 Pre-release** one from the **Releases Section ->**

Also, **minor fixes** have been posted in the support channel. Check the pins once you get in there (small thumbtack icon)

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

I'm [cacophony](https://github.com/cacophony-wj), a humble person. I haven't been modding long, but I want to provide a modlist until a bigger NSFW one is made.

I also want to make a list with a lot of options.

Finally I want a list for the casual gamer who maybe wants to indulge in a little heroic fantasy.

That said, I have been putting _NSFW_ content into games since the first _Nude Raider_ patch so I am familiar with it. 

While not as hard as Requiem, as packed as Living Skyrim, or as depraved as Lotus, if you want a basic Skyrim gameplay and sexual overhaul that offers many ways to have fun, you are welcome.

## A STRONG WARNING

## SexLab SE is still **beta!** It is still buggy!

Before posting a question to Discord, look at [Troubleshooting](#troubleshooting). Many common questions are answered there.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)
- [MEGA Account](https://mega.nz/aff=a94uEwwXPLU) (OPTIONAL BUT HIGHLY RECOMMENDED)
- A brain, eyes and time to read through this README

### System Specs

- CPU: >= 7th gen Intel processor OR >= AMD Ryzen 3000 series processor
- GPU: >= 1060, you need at least 6GB of VRAM
- RAM: >= DDR4 with at least 16GBs

Everything should be installed on an SSD that has at least 256GB of space available. Also check [Tweaking Performance](#tweaking-performance) if you want more FPS. **You won't be able to play the modlist with 4GB of VRAM**.

# Installation

##  Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to **Updating.** (#updating)

####  Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017 and 2019". <a href="https://aka.ms/vs/16/release/vc_redist.x64.exe">Direct link</a> if you can't find it.

####  Steam Config

**Disable the Steam Overlay**

The Steam Overlay can cause issues with ENB and is recommended to be turned off.

Open the Properties window (right click the game in your Library->Properties), navigate to the General tab and un-tick the Enable the Steam Overlay while in-game checkbox.

**Change Steam's Update Behavior**

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you and lock you out of playing your _Wabbajack_ modlist(s), head over to the Properties window, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_ while you're at it.

**Set the Game language to English**

Wabbajack will check your game files and make sure that we have the same version. This also means that any other language than English will fail the installation.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

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

###  Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD. You will also need an additional 30 GB beyond the modlists' official size to store temporary working files. It is not recommended to allow your drive to get over 90% full (red bar in File Explorer) so be sure to leave yourself a little headroom on top of all that.

    Adjust the Installation Location to a directory located on the root directory of one of your drives
    For example, this might be "C:\LeS", "D:\LeS", or "E:\LeS"
    Ensure the Download Location is within that directory
    Click the Go/Begin button
    Wait for Wabbajack to finish

##  Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**DO NOT CONTACT MOD AUTHORS DIRECTLY.**

**Could not download x:**

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till the modlist receives an update.

**x is not a whitelisted download:**

This can happen when update the modlist receives an update. Check if a new update to the modlist is available and wait if there is none.

**Wabbajack could not find my game folder:**

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the Pre-Installation step. If this still doesn't work, ensure that you are not running Wabbajack as an Administrator.

**MEGA files stuck at _100%_**

The files from MEGA are very large and must be verified. Please be extremely patient and allow each file to hash for at least 30 minutes, up to two hours if you are not using a solid-state drive. If you are certain you can't download the files any other way, try manual download from the Manifest in Wabbajack's lower-left corner.

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple Wabbajack lists. Sometimes it does anyway. Try signing up for a MEGA account, or if you have already done so, try logging out of it and downloading anonymously (although much more slowly).

**Wabbajack cannot continue because of unknown files.**

Move your downloads folder outside of your _LeS Directory_, ensure the _LeS Directory_ is clear of all files, then close and restart Wabbajack. Be sure to point the downloads box to your relocated downloads folder.

###  Post-Installation

**Copy Game Folder Files**

Download the latest ENB Series from [here](http://enbdev.com/download_mod_tesskyrimse.htm) and copy d3d11.dll and d3dcompiler_46e.dll to your game folder.

Copy all of the files from the _LeS Directory/game folder files_ directory to your game folder.

## To Launch the Game

Navigate to the directory where you installed the modlist _Licentia et Servitium_. Inside you will notice an executable file called _ModOrganizer.exe_. This file (the _Mod Organizer 2_ application) has already been automatically installed and configured by Wabbajack with all the necessary mods to run the modlist and does not need to be updated, replaced, or manually configured. Simply launch it when instructed below to continue.

##  Updating

**DO NOT UPDATE unless you have a CRITICAL BUG.**

First, check CHANGELOG.md. If you are not interested in the changes, or they do not address a bug you are having, **do not update**.

If you do update, copy out the entire _profiles_ folder within the _LeS_ directory to somewhere **you will remember.**

**This is your final warning, Wabbajack will delete your saves when updating!**

**To confirm: all saves, BodySlide customizations, and additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!**

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite_ button.

When the update is complete, **move** the _profiles_ folder back into the _Licentia et Servitium_ folder and choose **not** to overwrite. (Your saves will be restored but any modlist changes will be kept.)

Next **delete** the _profiles_ folder leftovers from your backup, as they only have old and useless files.

You should be ready to continue as per the installation instructions.

# Number One Rule: This List Is Customizable

Your kinks are a very private thing. I have included many mods for many purposes. They are almost all geared toward female submissive characters with particular fetishes but with a little tweaking you can get it the way you want. Most of the mods can be easily disabled via the in-game MCM menu.

# Misaligned Animations

I have included a ton of animations, almost the maximum, so people don't feel the need to pack in more. Many of them are less than perfect. If they are not aligned you will have to do it yourself. Here's how it works... the _L_ key on your keyboard moves you _forward,_ i.e. closer to your partner. _Shift-L_ moves you _backward,_ or the reverse. _;_ moves you _up_, or higher in elevation than your partner. _Shift-;_ does the reverse. Finally, _'_ moves you _Right_ compared to your partner, whereas _Shift-'_ moves you _Left_.

#  Admiring Yourself

For those who want to experience "POV" (point-of-view) scenes or to play primarily in first person, [Immersive First Person View](https://www.nexusmods.com/skyrimspecialedition/mods/22306) is included. It's a little wonky, so it's disabled by default. Ensure you're in first person mode (F key by default) and press _NUMPAD 0_ to enable it. Then press the F key again and look downward. Should work tolerably well for POV scenes (maybe a bit of clipping) except for animations where the actors are _really_ close to each other. 

**You cannot switch to third person anymore without deactivating IFPV with _NUMPAD 0_!**

To _disable IFPV_ once you have enabled it, ensure that you **can** see your body when you look downward, then press _NUMPAD 0_. You will automatically switch to a third person view. Once more the _F_ key will return to its default function, as will the scroll wheel.

You can always watch a scene from an external view with SexLab's default freecam available with _NUMPAD 3_. Use the mouse to look around and WASD to move your "camera".

# A Bit of a Note about "Combat Surrender"

All of the _SexLab_ death alternatives are a mess. I have wrestled with them for years. _Defeat_ is the worst of them all, but I included it so people can have their submission without their bondage. But it is incompatible with Cursed Loot's "Combat Surrender," and Combat Surrender, while still buggy, at least never renders it impossible to continue your game. So I have opted to leave Combat Surrender enabled. However, this comes with two side notes.

_If a person talks to you (defined by the game as friendly), then attacks you (defined by the game as hostile), then forces you to surrender, you will **always** be locked into a full set of extremely punishing bondage gear_. To fix this problem, await the next revision of _Cursed Loot_.

_If you are forced to surrender to a creature,_ this feature was initially disabled and tacked on later. Weird things will probably happen. You may even be gagged and turned over to a prison cell. To fix this problem, await the next revision of _Cursed Loot_.

You can also solve all of these problems by disabling "Combat Surrender" (or _Cursed Loot_ entirely) and dying like Skyrim intended you to.

# Arousal and Clockwork

Once you get the message about the collapsed passage north of Riften, it is recommended to disable _Cursed Loot_ if you are using that mod before exploring the introduction to _Clockwork_. Traveling to this area locks you into a zone with no way to return for about 5 - 10 playtime hours and no targets for SexLab interactions or vendor services. This will make it extremely difficult to relieve yourself or remove yourself from devices. A friendly tip from a helpful user.

# A word about ENBs

I have chosen _Re-Engaged_ as the ENB because best I can tell _Silent Horizons_ needs an update. I don't understand it, to me it's black magic. If you don't like it I have tested these:

_Silent Horizons_ was causing flicker for me. I think it needs an update, but you could always try it. I prefer it far more then _Re-Engaged._
_Hardlandson's_ is a great third choice with fantastic interiors and atmospheric fogs. Personally I think the exteriors are a little too washed out.
_PI-CHO_ looks great for character close-ups and resembles Silent Horizons for everything else, but the specular map for wet effects is a bit too bright for me.
_Rudy_ will technically work but is not recommended as it has no variant which supports Cathedral Weathers.
_Serio's ENB_ is probably the best ENB for customizing with the _Cathedral Weathers MCM_.
_lJoss_ is Lexy's new standard but requires darker lod mods and custom DynDOLOD settings that I do not use. This ENB is not compatible.

The other ENB's seemed either so inferior or were completely incompatible that I didn't mention them. I also left out any ENB preset that hasn't updated in over six months, since SSS support and the wet shader effect was added to the binaries.

# Crafting the Female Bodies

The women will look super weird if you don't provide them with customized bodies. Follow the steps in the below section.

[Female Bodies and Outfits](https://github.com/cacophony-wj/LeS/blob/master/BODYSLIDE.md)

# Game Settings - System and MCM

The next step is to configure the game. Launch the modlist from the command which reads **RUN ME TO START THE GAME**, create your character, and follow _all_ of the instructions in the below link:

[Licentia et Servitium Configuration](https://github.com/cacophony-wj/LeS/blob/master/MCMs.MD)

#  Adding Followers, Outfits, and Other Mods

This is not "officially" supported as per _Wabbajack Rule 11_. That said, I know you want to do it anyway, so I will offer this instruction.

**Screen Archery** by adding _Poser Mods_ is not supported. Download the _Cupid_ modlist for this purpose.

For _Gear_ it's as simple as adding it under _Added Mods_ and above _LEAVE HERE AT THE END_ in the left pane and the very bottom in the right pane. If your mod comes with _BodySlides_ (it should say so in the description) you will have to select them from the _Groups..._ menu and run them as per the instructions in the _Bodies_ section. If your gear mod does something crazy like add a huge museum of displays or put in chests for you to find you might have some issues. Otherwise, just use _AddItemMenu_ (in your inventory by default) to search for the item by name and put it in your inventory. _AddItem_ is the ultimate cheat so don't use it if you want to play the "game" part of the game. I leave it in because this list is mostly sexy people and I want players to look good exactly the way they want.

For _Follower Mods_ add them and enable them under _Added Mods_ and above _LEAVE HERE AT THE END_ in the left pane and just above _DynDOLOD_ in the right pane. If they have a lot of custom actions you will have to craft an _NFF Ignore Token_ and equip it on them after you recruit them. Be sure _not_ to "Import" *any* followers into the _Framework_ or everything will break. Also, do not recruit *any* followers that do not have a default "Follow me" option (or something similar). If you are unsure about your follower, read its description page and all compatibility notes for any problems with "Nether Follower Framework." If any are mentioned, you will probably need an Ignore Token. If your follower mod contains any quests to go along with them they may conflict with stuff or even cause buggy dark faces on main characters. No way to know for sure without being a modder.

Finally, I **_MIGHT_** support the addition of a handful of _Lover's Lab_ mods depending on what they are and how much time I have to troubleshoot. _DO NOT ASK ANYONE ELSE BUT ME **(cacophony#0001)** TO TROUBLESHOOT YOUR LOVER'S LAB MODS._ I will say from the beginning that many of them, such as mods that constantly scan for stuff like periods, pregnancies, breast milk, etc. always cause tons of problems in the end. I do not and can not support the addition of these mods. If you want them, play with them until they break and start the game over from a pre-configured save in the cell. I can almost guarantee that they will break unless you are extremely conservative. To solve all these issues would require knowledge that I don't have. 

It might be possible to squeeze in that kind of stuff on a more barebones version of Skyrim. If so, I invite you to download a simple "base" list from **#unofficial-modlist-submissions** to ensure you have critical fixes and then build your list up from scratch. You can always drop by **#NSFW-mod-discussion** to compare experiences.

All that said, if you can't figure out a mod on your own that I did not mention above, I may help you work it in on a case-by-case basis depending on how busy I am. It is expected that you have familiarity with Mod Organizer 2, xEdit, FNIS, Nemesis, and basic knowledge of what an override patch is before you try to do anything beyond basic outfit or follower additions.

Finally _do not ask about non-Lover's lab mods_ except really simple things like makeup, hair, outfits, or voice tracks. I do not have the time to write custom patches for these. And just to make it clear, _DO NOT ASK ANYONE ELSE BUT ME **(cacophony#0001)** TO TROUBLESHOOT YOUR LOVER'S LAB MODS._ Rule 11 fully applies to everyone else but me.

# Removing the Modlist

You can just remove the _LeS_ folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

# Contact

I am regularly available on the [Wabbajack Discord](https://discord.gg/wabbajack) (`#nsfw-mod-discussion`) (`#licentia-et-servitium-support).

# Contributing

See [Contributing](CONTRIBUTING.md).

# Changelog

See [Changelog](CHANGELOG.md).
