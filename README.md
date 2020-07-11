# Licentia et Servitium

![Status](https://img.shields.io/endpoint?url=https://build.wabbajack.org/lists/status/LeS/badge.json)
![Installs](https://img.shields.io/endpoint?url=https://build.wabbajack.org/metrics/badge/LeS/total_installs_badge.json)

- [Licentia et Servitium](#licentia-et-servitium)
- [Licentia et Servitium: A Modest Sampling of Lover's Lab](#licentia-et-servitium-a-modest-sampling-of-lovers-lab)
	- [BEFORE YOU CONTINUE:](#before-you-continue)
	- [Preamble](#preamble)
		- [Wabbajack](#wabbajack)
	- [A STRONG WARNING](#a-strong-warning)
	- [SexLab SE is still in **late beta!** Expect bugs!](#sexlab-se-is-still-in-late-beta-expect-bugs)
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
	- [Updating](#updating)
	- [Number One Rule: This List Is Customizable](#number-one-rule-this-list-is-customizable)
	- [A Note on SexLab for the Uninitiated](#a-note-on-sexlab-for-the-uninitiated)
	- [Admiring Yourself](#admiring-yourself)
	- [Specific Mods](#specific-mods)
	- [Crafting the Female Bodies](#crafting-the-female-bodies)
	- [Game Settings - System and MCM](#game-settings---system-and-mcm)
	- [A word about ENBs](#a-word-about-enbs)
	- [Adding Followers, Outfits, and Other Mods](#adding-followers-outfits-and-other-mods)
	- [Removing the Modlist](#removing-the-modlist)
	- [Contact](#contact)
	- [Contributing](#contributing)
	- [Changelog](#changelog)

# Licentia et Servitium: A Modest Sampling of Lover's Lab

## BEFORE YOU CONTINUE: 

Check to see if there is a more recent version in the Github RELEASES section. It should only take a few minutes to update.

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

I'm [cacophony](https://github.com/cacophony-wj), a humble Wabbjack modlist developer with only marginal experience, but I have created this modlist to fill an essential void while Wabbajack's primary _NSFW_ list is under maintenance. 

A secondary objective was to create a single list to fill multiple purposes based on how most people use _Lover's Lab_.

Finally I wanted a list for the casual gamer, one who maybe hadn't the experience of much beyond vanilla Skyrim and doesn't currently feel like learning a bunch of new systems.

That said, I have been modding _NSFW_ content into games since the first _Nude Raider_ patch so I like to think I know my way around the basics. 

While not as full-featured as many lists, if you want a basic Skyrim gameplay and sexual overhaul that offers options for characters of multiple optional identities and fetishes, you are welcome here.

### Wabbajack

Somewhat important section for people that don't know what Wabbajack is and how it works.

Let's start with some terminology: `Modpack` vs `Modlist`

**Modpack**:
Commonly found in the Minecraft modding scene, a modpack is a collection of mods put together in a single file. Often compressed into a zip, 7z or rar archive, this single file contains an entire modding setup and is very large in size as every file from every mod is included. Uploading a Modpack to the Internet means distributing possible copyrighted content and has lead to huge backlash in other modding scenes.

**Modlist (written guide)**:
A written guide like STEP, Lexys LOTD SE Mod Guide or The Phoenix Flavour that tells the user what, when, and how to download and install an effective combination of mods. In order to reproduce the same setup of the guide author you will pick up a lot of new modding tricks and learn many things previously unknown to you. Depending on the depth of the guide, process not only takes a very long time but is very error prone if the user does not read everything extremely carefully and repeat it exactly.

**Modlist (Wabbajack)**:
A Wabbajack Modlist can be compared to a written guide except it is not written for humans but for machines. The resulting _.wabbajack_ file contains instructions on what, when, and how to download and install a combination of mods in order to replicate the entire setup of the author without bundling any assets.

Now lets talk about Wabbajack:

Wabbajack is an automated Modlist installer that can recreate contents of a folder on another machine without ever distributing copyrighted materials or syncing data between the source and destination machine. Wabbajack will create instructions for a Modlist when compiling, those can be as simple as _Download Mod abc from the Nexus_ or complex as _Build BSAs from scratch using the following files_.

Wabbajack came into existing around July 2019 and the community has been growing past the 18 thousand mark with hundreds of daily users. The start was somewhat bumpy, because a lot of people, especially mod authors, had {and sometimes still have) no idea what Wabbajack does and simply think it's some kind of Modpack thing. If you want more information checkout, our website at [wabbajack.org](https://www.wabbajack.org/), made by [erri120](https://github.com/erri120)].

## A STRONG WARNING

## SexLab SE is still in **late beta!** Expect bugs!

Before posting a question to one of the _NSFW_ Discord channels, refer to [Troubleshooting](#troubleshooting). Many common questions are answered there.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)
- [VectorPlexus Account](https://vectorplexus.com/)
- [MEGA Account](https://mega.nz/aff=a94uEwwXPLU) (OPTIONAL BUT HIGHLY RECOMMENDED)
- A brain, eyes and time to read through this README

You can also install any Wabbajack Modlist without a Nexus Premium account but you will have to download each file manually. A MEGA account as an optional requirement because there are some big files on MEGA that need to be downloaded. You don't need one but MEGA has a limit on how much an anonymous user can download.

You can login to various sites using the internal login manager in Wabbajack. It can be accessed using the gear icon in the top right corner. Your credentials are encrypted and can only be decrypted on your machine as your current user, see [`ProtectedData` Class](https://docs.microsoft.com/en-us/dotnet/api/system.security.cryptography.protecteddata?view=netframework-4.8) and [DPAPI](https://en.wikipedia.org/wiki/Data_Protection_API) for more information.

### System Specs

- CPU: >= 7th gen Intel processor OR >= AMD Ryzen 3000 series processor
- GPU: >= 1060, you need at least 6GB of VRAM
- RAM: >= DDR4 with at least 16GBs

Everything should be installed on an SSD that has at least 256GB of space available. Also check [Tweaking Performance](#tweaking-performance) if you want more FPS. **You won't be able to play the modlist with 4GB of VRAM&**.

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

I highly recommend uninstalling the game through Steam, deleting the game folder and reinstalling it. You should also clean up the Skyrim Special Edition folder in Documents/My Games/. If you have download throttles or caps, or just don't want to wait, you can also use <a href="https://www.nexusmods.com/skyrimspecialedition/mods/30133">Skyrim Shredder</a> by trawz to clean your installation.

**Start Skyrim**

After you have done everything above and have a clean SSE installation ready, start the Launcher and open the Options menu.

    Click on Ultra
    Set the Aspect Ratio and Resolution to your monitor's native values
    Set Antialiasing to Off
    Uncheck Windowed Mode and Borderless

Start the game and exit once you're in the main menu.

##  Using Wabbajack

###  Downloading and Installing

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

    Open Wabbajack
    Load the Modlist from Disk
    Adjust the download and installation paths
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

Download the latest ENB Series from <a href="http://enbdev.com/download_mod_tesskyrimse.htm">here</a> and copy d3d11.dll and d3dcompiler_46e.dll to your game folder.

Copy all of the files from the _LeS Directory/game folder files_ directory to your game folder.

##  Updating

**If you are in the middle of a playthrough, DO NOT UPDATE unless something in your game is broken.**

**It is possible that you will have problems with an old save if you update and then try to play very long with it.**

First, check the Changelog before doing anything. If you are not interested in the changes, or they do not address a bug you are having, **do not update**.

If you're going to ignore my advice and try to continue a save anyway, copy out the entire _profiles_ folder within the _LeS_ directory to somewhere **you will remember.**

Next, **move** the _BodySlide Output_ folder within the _mods_ folder to the root directory that _Licentia et Servitium_ is on (otherwise it'll take forever). **Importantly, remember where you did this.**

**This is your final warning, Wabbajack will delete all files that are not part of the Modlist when updating!**

**To confirm: all saves, BodySlide customizations, and additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!**

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing Modlist_ button.

When the update is complete, **move** the _profiles_ folder back into the _Licentia et Servitium_ folder and choose **not** to overwrite. (Your saves will be restored but any configurations changed by the update will be kept.)

Next **delete** the _profiles_ folder leftovers from your backup, as they only have old and useless files.

Finally, **move** the _BodySlide Output_ folders back into the _mods_ folder and **do** choose to overwrite in case I've bone-headedly left something in there.

You should be ready to continue as per the installation instructions.

## Number One Rule: This List Is Customizable

Your kinks are a very private thing. There's no way I can create a list that appeals to everyone, so I have included many mods for many purposes. They are almost all geared toward female submissive characters with particular fetishes but with a little tweaking you can get it the way you want. Most of the mods can be easily disabled via the in-game MCM menu, and many of them aren't mastered into anything so they can be disabled entirely in MO2. The only merge is for my CR patches which can be easily undone and disabled for the particular mod you don't want to use.

##  A Note on SexLab for the Uninitiated

_Skyrim_ was never designed to have animations injected into it. It most certainly was never intended to pair two actors in a close space and perfectly align them for a sex scene. Animators do a lot of the work, but the engine is far from ideal. On top of that, there are many poorly aligned animations out there. In any case, no matter how good your animations, you will often find problems like: people kissing the air, _parts_ not going _into_ each other, characters floating above the ground, or even more wacked-out stuff like falling into the ground, clipping into furniture, or people going invisible. Fortunately, SexLab allows you to correct _some_ of this with manual positioning for each animation. Here's how it works... the _L_ key on your keyboard moves you _forward,_ i.e. closer to your partner. _Shift-L_ moves you _backward,_ or the reverse. _;_ moves you _up_, or higher in elevation than your partner. _Shift-;_ does the reverse. Finally, _'_ moves you _Right_ compared to your partner, whereas _Shift-'_ moves you _Left_. (Or maybe the other left.) Get used to these, you'll be using them a lot.

##  Admiring Yourself

For those who want to experience POV scenes or to play primarily in first person, [Immersive First Person View](https://www.nexusmods.com/skyrimspecialedition/mods/22306) is included. It's a little wonky, so it's disabled by default. Ensure you're in first person mode (F key by default) and press _NUMPAD 0_ to enable it. Then press the F key again and look downward. Should work tolerably well for POV scenes (maybe a bit of clipping) except for animations where the actors are _really_ close to each other. 

**You cannot switch to third person anymore without deactivating IFPV with _NUMPAD 0_!**

To _disable IFPV_ once you have enabled it, ensure that you **can** see your body when you look downward, then press _NUMPAD 0_. You will automatically switch to a third person view. Once more the _F_ key will return to its default function, as will the scroll wheel. _If you are on Light but Kinky, please note issues with IFPV in the [Troubleshooting](https://github.com/cacophony-wj/LeS/blob/master/TROUBLESHOOTING.md) section._

You can always watch a scene from an external view with SexLab's default freecam available with _NUMPAD 3_. Use the mouse to look around and WASD to move your "camera".

## Specific Mods

This section goes into further detail about invididual mod setups in the modlist and, while informative, not strictly necessary if you just want to play the game. Keep in mind that I basically paraphrased from the _Lotus_ README.

[Important NSFW Mods You Should Know About](https://github.com/cacophony-wj/LeS/blob/master/NSFW.md)

[Important SFW Mods You Should Know About](https://github.com/cacophony-wj/LeS/blob/master/SFW.md)

## Crafting the Female Bodies

The women will look super weird if you don't build them. Follow the steps in the below section.

[Female Bodies and Outfits](https://github.com/cacophony-wj/LeS/blob/master/BODYSLIDE.md)

## Game Settings - System and MCM

The next step is to configure the game. Launch _Skyrim: Special Edition_ from the **RUN ME** command, create your character, and follow _all_ of the instructions in the below link:

[Licentia et Servitium Configuration](https://github.com/cacophony-wj/LeS/blob/master/MCMs.MD)

## A word about ENBs

The weather and lighting mods I have in this list look best with _Silent Horizons_, and I have tried almost a dozen of them. However, it's very vibrant, bloomy, and "cartoony", so feel free to swap out as you see fit, but keep in mind these notes and warnings:

_Re-Engaged_ is probably the best runner-up because it has the best overall "realistic" look but I like things a little more vibrant.
_Hardlandson's_ is a great third choice with fantastic interiors and atmospheric fogs. Personally I think the exteriors are a little too washed out.
_PI-CHO_ looks great for character close-ups and resembles Silent Horizons for everything else, but glare and shine in wet or rainy areas almost looks like fireworks.
_Rudy_ will technically work but is not recommended as it has no variant which supports Cathedral Weathers.
_Serio_ is probably the best ENB for customizing the Cathedral imagespaces with the MCM.
_lJoss_ is Lexy's new standard but requires darker lod mods and custom DynDOLOD settings that I do not use. I do not recommend this option.

The other ENB's seemed either so inferior or were completely incompatible that I didn't mention them. I also left out any ENB preset that hasn't updated in over six months, since SSS support and the wet shader effect was added to the binaries.

##  Adding Followers, Outfits, and Other Mods

This is not "officially" supported as per _Wabbajack Rule 11_. That said, I know you want to do it anyway, so I will offer this instruction.

**Screen Archery** by adding _Poser Mods_ is not supported. Download the _Cupid_ modlist for this purpose.

For _Gear_ it's as simple as adding it under _Added Mods_ and above _BodySlide Output - LEAVE HERE AT THE END_ in the left pane and the very bottom in the right pane. If your mod comes with _BodySlides_ (it should say so in the description) you will have to select them from the _Groups..._ menu and run them as per the instructions above. If your gear mod does something crazy like add a huge museum of displays or put in chests for you to find you might have some issues. Otherwise, just use _AddItemMenu_ (in your inventory by default) to search for the item by name and put it in your inventory. _AddItem_ is the ultimate cheat, by the way, so don't use it if you want to play the "game" part of the game. I leave it in because this list is mostly sexy people and I want players to look good exactly the way they want.

For _Follower Mods_ add them and enable them under _Added Mods_ and above _BodySlide Output - LEAVE HERE AT THE END_ in the left pane and just above _DynDOLOD_ in the right pane. If they have a lot of custom scripting, you will have to craft an _NFF Ignore Token_ and equip it on them after you recruit them. Be sure _not_ to "Import" *any* followers into the _Framework_ or everything will break. Also, do not recruit *any* followers that do not have a default menu option to do so. If you are unsure about your follower, read its description page and all compatibility notes for any problems with "Nether Follower Framework." If any are mentioned, you will probably need an Ignore Token. If your follower mod contains any _world or cell edits_ (changes to game spaces handled in my modlist), there may be more severe conflicts. This usually only happens if the Follower has quests to go along with them. No way to know for sure unless you "filter for conflicts" with _SSEEdit._

Finally, I **_MIGHT_** support the addition of a handful of _Lover's Lab_ mods depending on what they are and how much time I have to troubleshoot. _DO NOT ASK ANYONE ELSE BUT ME **(cacophony#0001)** TO TROUBLESHOOT YOUR LOVER'S LAB MODS._ I will say from the beginning that many of them, such as mods that constantly scan for changes in the player, other people, or creatures are especially bad for _cloak scripts_ that never terminate. This includes mods that let your hair grow, your boobs get full of milk, or god forbid give every woman in Tamriel a menstrual cycle. I do not and can not support the addition of these mods. If you want them, play with them until they break and start the game over from a pre-configured save in the cell. I can almost guarantee that they will break unless you are extremely conservative. To solve all these issues would require knowledge of Papyrus coding which I do not possess. 

It might be possible to squeeze in a greater amount of such mods on a more barebones version of Skyrim. If so, I invite you to download a simple "base" list from **#unofficial-modlist-submissions** to ensure you have critical fixes and then build your list up from scratch. You can always drop by **#NSFW-mod-discussion** to compare experiences.

Before asking about adding a mod, read the list below. I **will not** help you add any of these to _Licentia et Servitium_ or any other list. And I hate to say it but I can almost guarantee significant difficulties if you try to use more than one of them at a time. I am not saying they are "bad" mods, just that they are difficult to implement or maybe just incompatible with my setup. 

	- Egg Factory
	- Estrus Chaurus
	- EstrusForSkyrimSE
	- Fall of the Dragonborn SSE
	- Fertility Mode
	- Fill Her Up SE
	- Horny Creatures of Skyrim
	- Horrible Harrassment
	- Horrible Harrassment for Him SE
	- Immersive Hair Growth and Styling
	- Milk Addict SE
	- Milk Mod Economy SE (Full or Light)
	- Mini SSE Needs
	- Sanguine's Debauchery Enhanced
	- Scent of Sex SE
	- Sexlab Approach Redux (For Her or For Him)
	- Sexlab Hentai Pregnancy Special Edition
	- Sexlab Survival Special Edition
	- Skooma Whore SE
	- SL Separate Orgasm SE
	- SlaveTats
	- The Milk Maid SE
	- The Sisterhood of Dibella

**The above list is incomplete.** I will also not support or convert any mods listed as _unstable, beta, or uncoverted_ on _Lover's Lab_. This includes a few big ones like Sanguine's Debauchery and Slaverun Reloaded. For a full list of converted and unconverted mods, check the _Conversion Tracking_ pin in **#NSFW-mod-discussion**.

All that said, if you can't figure out a mod on your own that I did not mention above, I may help you work it in on a case-by-case basis depending on how busy I am. It is expected that you have familiarity with Mod Organizer 2, xEdit, FNIS, Nemesis, and a touch of conflict resolution before you try to do anything beyond basic outfit additions.

Finally _do not ask about non-Lover's lab mods_ except really simple things like makeup, hair, outfits, or voice tracks. I do not have the time to write custom patches for these. And just to make it clear, _DO NOT ASK ANYONE ELSE BUT ME **(cacophony#0001)** TO TROUBLESHOOT YOUR LOVER'S LAB MODS._ Rule 11 fully applies to everyone else but me.

## Removing the Modlist

You can just remove the _LeS_ folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Contact

I am regularly available on the [Wabbajack Discord](https://discord.gg/wabbajack) (`#nsfw-mod-discussion`) (`#licentia-et-servitium-support).

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
