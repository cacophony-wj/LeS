
(https://img.shields.io/endpoint?url=https://build.wabbajack.org/metrics/badge/LeS/total_installs_badge.json)
(https://img.shields.io/endpoint?url=https://build.wabbajack.org/lists/status/LeS/badge.json)

# Licentia et Servitium: A Double-Sided Coin of Lover's Lab

[Licentia et Servitium: A Double-Sided Coin of Lover's Lab](#licentia-et-servitium-a-double-sided-coin-of-lovers-lab)
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
	- [LBS vs. LBK, How Do I Choose?](#lbs-vs-lbk-how-do-i-choose)
	- [Important Mods you should know about](#important-mods-you-should-know-about)
	- [NSFW Mods](#nsfw-mods)
		- [SexLab - Frameworks](#sexlab---frameworks)
		- [Devious Devices](#devious-devices)
		- [SexLab - Others](#sexlab---others)
		- [Nomkaz](#nomkaz)
	- [SFW Mods](#sfw-mods)
		- [Dragons](#dragons)
		- [Animals](#animals)
		- [Followers](#followers)
		- [Transformations](#transformations)
	- [(MORE TO BE ADDED LATER)](#more-to-be-added-later)
	- [Female Bodies And Armors](#female-bodies-and-armors)
		- ["BodyGen4"](#bodygen4)
		- [Running BodySlide](#running-bodyslide)
	- [A bit of a note on schlongs and strap-ons](#a-bit-of-a-note-on-schlongs-and-strap-ons)
	- [The below sections will be reworked and relocated](#the-below-sections-will-be-reworked-and-relocated)
	- [A Note on SexLab for the Uninitiated](#a-note-on-sexlab-for-the-uninitiated)
	- [Admiring Yourself](#admiring-yourself)
	- [Specific to Light But Sexy](#specific-to-light-but-sexy)
		- [Defeat](#defeat)
	- [Specific to Light But Kinky](#specific-to-light-but-kinky)
		- [Cursed Loot](#cursed-loot)
	- [Best Save Practices: READ ME!](#best-save-practices-read-me)
	- [A word about ENBs](#a-word-about-enbs)
	- [Adding Followers, Outfits, and Other Mods](#adding-followers-outfits-and-other-mods)
- [A bit of a note on System Settings: IMPORTANT!](#a-bit-of-a-note-on-system-settings-important)
	- [Settings](#settings)
		- [Gameplay](#gameplay)
		- [Display](#display)
	- [Controls](#controls)
	- [Game MCM Options](#game-mcm-options)
		- [SexLab](#sexlab)
			- [Install](#install)
			- [Rebuild & Clean](#rebuild--clean)
			- [Animation Settings](#animation-settings)
			- [Sex Diary](#sex-diary)
		- [SAVE AND LOAD!](#save-and-load)
		- [SL Anim Loader](#sl-anim-loader)
			- [General Options](#general-options)
		- [A Matter of Time](#a-matter-of-time)
			- [Presets](#presets)
		- [AGO](#ago)
			- [Settings](#settings-1)
		- [Cathedral Weather](#cathedral-weather)
			- [Settings](#settings-2)
		- [CGO](#cgo)
			- [Settings](#settings-3)
		- [Cursed Loot](#cursed-loot-1)
			- [Debug](#debug)
		- [Deadly Dragons](#deadly-dragons)
			- [Dragons](#dragons-1)
		- [Devious Devices Helpers](#devious-devices-helpers)
			- [Basic Settings](#basic-settings)
		- [Extended UI](#extended-ui)
			- [Stats Menu](#stats-menu)
		- [Follower Framework](#follower-framework)
			- [System](#system)
		- [GIST Soul Trap](#gist-soul-trap)
			- [Main](#main)
			- [Leveling](#leveling)
		- [LOTD Settings](#lotd-settings)
			- [General](#general)
		- [Moonlight Tales](#moonlight-tales)
			- [Tools](#tools)
		- [Quick Light](#quick-light)
		- [Sacrosanct Vampires](#sacrosanct-vampires)
			- [Vampire Spells, Powers and Abilities](#vampire-spells-powers-and-abilities)
		- [SexLab Aroused](#sexlab-aroused)
			- [Settings](#settings-4)
		- [SexLab Eager NPCs](#sexlab-eager-npcs)
			- [General](#general-1)
		- [SexLab Solutions](#sexlab-solutions)
			- [follower](#follower)
			- [Miscellaneous](#miscellaneous)
		- [SexLab Tools](#sexlab-tools)
			- [Settings](#settings-5)
		- [Sky UI](#sky-ui)
			- [General](#general-2)
			- [Controls](#controls-1)
		- [SLA Monitor Widget](#sla-monitor-widget)
			- [Scanner Settings](#scanner-settings)
			- [Widget Looks](#widget-looks)
		- [Storm Lightning](#storm-lightning)
			- [Presets](#presets-1)
			- [Advanced](#advanced)
		- [Summermyst Enchantments](#summermyst-enchantments)
		- [Trade & Barter](#trade--barter)
			- [Barter Rates](#barter-rates)
		- [Ultimate Combat](#ultimate-combat)
			- [General](#general-3)
			- [NPC Setting](#npc-setting)
		- [Wildcat Combat](#wildcat-combat)
			- [Stamina Costs](#stamina-costs)
			- [Injuries](#injuries)
			- [Timed Block](#timed-block)
			- [difficulty](#difficulty)
		- [XPMSE](#xpmse)
		- [ZaZ Animation Pack](#zaz-animation-pack)
			- [SexLab](#sexlab-1)
		- [Defeat](#defeat-1)
			- [General Settings](#general-settings)
	- [All done!](#all-done)
	- [Troubleshooting](#troubleshooting)
		- [What are all these Form 43 warnings? I thought Form 43 was bad news.](#what-are-all-these-form-43-warnings-i-thought-form-43-was-bad-news)
		- [Why are there so many duplicated animation folders? _or_ Why do I have to CTRL-CLICK to build _BodySlide_?](#why-are-there-so-many-duplicated-animation-folders-or-why-do-i-have-to-ctrl-click-to-build-bodyslide)
		- [I tried to wear a piece of gear but my body disappeared!](#i-tried-to-wear-a-piece-of-gear-but-my-body-disappeared)
		- [My skin pokes through my armor! or My bald head pokes through my hood!](#my-skin-pokes-through-my-armor-or-my-bald-head-pokes-through-my-hood)
		- [Some of me is too _jiggly_! (Especially the belly.)](#some-of-me-is-too-jiggly-especially-the-belly)
		- [I read a skill book but my skill didn't go up!](#i-read-a-skill-book-but-my-skill-didnt-go-up)
		- [I'm running _Light But Kinky_ and I can't find my save!](#im-running-light-but-kinky-and-i-cant-find-my-save)
		- [The head bob is making me sick! I want to turn it off!](#the-head-bob-is-making-me-sick-i-want-to-turn-it-off)
		- [CGO isn't leaning / dodging! _or_ When I go into an adult scene, I hear sounds and voices but they just stand there!](#cgo-isnt-leaning--dodging-or-when-i-go-into-an-adult-scene-i-hear-sounds-and-voices-but-they-just-stand-there)
		- [I did all that but the things are still just standing there, especially when I get assaulted.](#i-did-all-that-but-the-things-are-still-just-standing-there-especially-when-i-get-assaulted)
		- [My arms won't go into a binder _or_ my hands are floating outside of my bindings _or_ my gag won't go in my mouth _or_ one of these is true for an NPC.](#my-arms-wont-go-into-a-binder-or-my-hands-are-floating-outside-of-my-bindings-or-my-gag-wont-go-in-my-mouth-or-one-of-these-is-true-for-an-npc)
		- [I'm locked into some gear and I can't move in third person.](#im-locked-into-some-gear-and-i-cant-move-in-third-person)
		- [I'm playing _Light But Kinky_ and I'm in such an incredible amount of bondage gear that I can't do anything at all!](#im-playing-light-but-kinky-and-im-in-such-an-incredible-amount-of-bondage-gear-that-i-cant-do-anything-at-all)
		- [I want creatures in _Light But Sexy_!](#i-want-creatures-in-light-but-sexy)
		- [Stuff is disabled. Did you forget? Or, can I enable it all, for the best of both worlds?](#stuff-is-disabled-did-you-forget-or-can-i-enable-it-all-for-the-best-of-both-worlds)
	- [Gameplay Tips - Walkthroughs - Light Spoilers for the Hopelessly Stuck.](#gameplay-tips---walkthroughs---light-spoilers-for-the-hopelessly-stuck)
		- [I was locked up in the "princess" start and something defeated me and I got teleported somewhere and the quest was completely broken! This isn't fair!](#i-was-locked-up-in-the-princess-start-and-something-defeated-me-and-i-got-teleported-somewhere-and-the-quest-was-completely-broken-this-isnt-fair)
		- [I can't find those damn keys in the _Light But Kinky_ "princess" start!](#i-cant-find-those-damn-keys-in-the-light-but-kinky-princess-start)
		- [Where the hell do I go after Chloe tells me about the secret passage?](#where-the-hell-do-i-go-after-chloe-tells-me-about-the-secret-passage)
		- [I was bound and then defeated and then teleported somewhere and now I can't get up from the ground!](#i-was-bound-and-then-defeated-and-then-teleported-somewhere-and-now-i-cant-get-up-from-the-ground)
	- [Removing the Modlist](#removing-the-modlist)
	- [Contact](#contact)
	- [Contributing](#contributing)
	- [Changelog](#changelog)

## BEFORE YOU CONTINUE: 

Check to see if there is a more recent version in the Github RELEASES section. It should only take a few minutes to update.

## Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

I'm [cacophony](https://github.com/cacophony-wj), a humble Wabbjack modlist developer with only marginal experience, but I have created this modlist to fill an essential void while Wabbajack's primary _NSFW_ list is under maintenance. 

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

##  LBS vs. LBK, How Do I Choose?

Your kinks are a very private thing. There's no way I can create a list that appeals to everyone, so I have included two lists each centered around the most common uses for Lover's Lab for you to choose from.

_Light But Sexy_ is the primary list, primarily intended to offer the option to have sex with attractive people as you play through a significantly modded Skyrim. Those choosing to play male characters or non-submissive females should choose this option so they don't find themselves intruded upon. Sexy roleplay is available via _Amorous Adventures_ which features full voice acting (despite incredibly cheesy dialog and quests), _SexLab Solutions_ which lets you pass varying skill checks by offering your (or your follower's) body, and _SexLab Eager NPCS_ (also known as "SLEN") which uses a rudimentary seduction system to improve your relationship with others via sex. Defeat, although fairly buggy as a death alternative, is also included to make combat sacrifices an option.

_Light But Kinky_ is the sublist for the well, kinky among us, and it is all about the _Cursed Loot_. Basically you will be fighting against magical traps that lock you in various restraining devices with little hope of escape, making yourself available to be exploited by anyone who might happen to be around. Given that _Devious Devices_ have no male body models (or only very limited ones) and you will find yourself having a lot of shall we say, "surprise" sex, this modlist is only recommended for female submissive characters. _Cursed Loot_ also has a death and surrender alternative with of course further bondage options, and rudimentary creature support is included.

Even though it is far more niche, _Light But Kinky_ is enabled by default. This is because more armors need to be built for it and I wished to combine all steps. If you wish to play _Light But Sexy_, first complete the steps in [Building Bodies and Armors with BodySlide](#building-bodies-and-armors-with-bodyslide) and then select _Light But Sexy_ from the main "profiles" dropdown in the center-top of MO2. No further steps are required.

## Important Mods you should know about

This section contains information about some of the most important mods in this setup. I made this section so end-users know exactly what mods change what and can read-up on stuff they find interesting as well as give props to the mod authors.

## NSFW Mods

### SexLab - Frameworks

You know this would be first, didn't you...
[SexLab Framework](https://www.loverslab.com/topic/91861-sexlab-framework-se-163-beta-8-november-22nd-2019/) is the core of all installed LL mods. Do note that this is a **beta build**. [SLAL](https://www.loverslab.com/files/file/5328-sexlab-animation-loader-sse/) or _SexLab Animation Loader_ and [SexLab Aroused Redux](https://www.loverslab.com/files/file/5482-sexlab-aroused-redux-sse-version-29/) are included as well.

The _Light but Kinky_ variant includes [Creature Framework](https://www.loverslab.com/files/file/5462-creature-framework-se/) and [More Nasty Critters](https://www.loverslab.com/files/file/4130-more-nasty-critters-slal-edition/).

[ZAZ](https://www.loverslab.com/files/file/5957-zaz-animation-packs-for-se/) is a requirement for other mods so you get that and the [ZAZ 8.0+ CBBE HDT Rev3](https://mega.nz/#!WEgGDaCa!wAho2Rphy47Lcd55DEmV50GgN07CMnTjhQ_r9s6dq-I) version.

Links:

- [SexLab Framework SE](https://www.loverslab.com/topic/91861-sexlab-framework-se-163-beta-8-november-22nd-2019/)
- [SexLab Animation Loader SSE](https://www.loverslab.com/files/file/5328-sexlab-animation-loader-sse/) by [Andreis](https://www.loverslab.com/profile/1770706-andreis/)
- [SexLab Aroused Redux SSE Version](https://www.loverslab.com/files/file/5482-sexlab-aroused-redux-sse-version-29/) by [fishburger67](https://www.loverslab.com/profile/441678-fishburger67/)
- [Creature Framework SE](https://www.loverslab.com/files/file/5462-creature-framework-se/) original by [Ep1cL3w7z](https://www.loverslab.com/profile/67752-ep1cl3w7z/)
- [More Nasty Critters Special Edition](https://www.loverslab.com/files/file/4130-more-nasty-critters-slal-edition/) by [MadMansGun](https://www.loverslab.com/profile/71862-madmansgun/)
- [ZAZ Animation Packs for SE](https://www.loverslab.com/files/file/5957-zaz-animation-packs-for-se/)
- [ZAZ 8.0+ CBBE HDT Rev3](https://mega.nz/#!WEgGDaCa!wAho2Rphy47Lcd55DEmV50GgN07CMnTjhQ_r9s6dq-I)

### Devious Devices

[Devious Devices](https://www.loverslab.com/topic/99700-devious-devices-se-43/) or DD for short is a very interesting mod and the foundation for [Devious Skyrim](https://www.loverslab.com/topic/30855-devious-skyrim/) (you should definitely read that post if you are into BDSM content). The conversion to SSE is a bit... funky to say the least but they finally build the SKSE plugin for 2.0.17. The conversion contains all three base mods: [Assets](https://www.loverslab.com/files/file/269-devious-devices-assets/), [Expansion](https://www.loverslab.com/files/file/1305-devious-devices-expansion/) and [Integration](https://www.loverslab.com/files/file/371-devious-devices-integration/).

The outfit conversions in the base DD AIO are incompatible with the body type I use so [3BA Bodyslides for Devious Devices](https://www.loverslab.com/files/file/11938-3ba-bodyslides-for-devious-devices-43-aio/) is included to help with that.

DD alone does not do much as a framework. The biggest gameplay mod for DD is DCUR aka [Deviously Cursed Loot](https://www.loverslab.com/topic/33986-deviously-cursed-loot-v85-2020-03-24/). This mod is *huge*. Takes like 20mins to do the MCM and you should, no, you _must_ read up on it _thoroughly_ if you want to customize it. I have tried my best at configuring this mod in a way that makes sense and enables you to actually play the game without being tied up, locked up or assaulted every 5 meters. The main premise of this mods still stands:

> Cursed Loot is a bondage and domination (BD) themed mod that will get you into trouble of the erotic kind when playing Skyrim. Beware when looting containers and defeated enemies in Skyrim!

There are dangers in Skyrim, mainly in Dungeons, that will keep you on guard and are more of an exception than a rule to make them more impactful. I will try tweaking the config more over time so be sure to voice your opinion (see [Contact](#contact)).

[Devious Devices Helpers](https://www.loverslab.com/files/file/9197-devious-devices-helpers-se/) counteracts all the restraints and makes your followers smarter when it comes to dealing with them.

> While playing with Deviously Cursed Loot and other Devious Devices mods, I found that my character being tied up and helpless was amusing for about five minutes.

This is what I am going for: have fun for some time but then get back to playing the game. The combination of Cursed Loot and Helpers should hopefully provide that gameplay experience. The entire thing is still experimental so expect tweaks to come over time.

Some big DD mods like [Sanguines Debauchery](https://www.loverslab.com/topic/120107-skyrimlldeepbluefrog-mods-conversion-to-sse/#comments) are not yet ready for SSE.

Links:

- [Devious Devices SE](https://www.loverslab.com/topic/99700-devious-devices-se-43/)
- [3BA Bodyslides for Devious Devices](https://www.loverslab.com/files/file/11938-3ba-bodyslides-for-devious-devices-43-aio/) by [Grummkol](https://www.loverslab.com/profile/2854288-grummkol/)
- [Devious Devices Helpers SE](https://www.loverslab.com/files/file/9197-devious-devices-helpers-se/) original by [TurboNerd](https://www.loverslab.com/profile/1172444-turbonerd/) converted by [nomkaz](#nomkaz)

### SexLab - Others

The following mods have a more _supportive_ role and do not fit any of the other categories.

[SexLab Aroused Monitor Widget](https://www.loverslab.com/files/file/11466-sexlab-aroused-monitor-widget-se/) adds a little widget that displays the arousal levels of nearby actors.

[SexLab Tools](https://www.loverslab.com/files/file/2018-sexlab-tools-v30/) gives you tools to control a scene.

[Sexlab LightMeUp](https://www.loverslab.com/files/file/8275-sexlab-lightmeup/) will illuminate the current SexLab scene so you don't have to pull out any additional torches and can actually see whats happening.

Links:

- [SexLab Aroused Monitor Widget SE](https://www.loverslab.com/files/file/11466-sexlab-aroused-monitor-widget-se/) original by [BeamerMiasma](https://www.loverslab.com/profile/424489-beamermiasma/) converted by [Ecohex](https://www.loverslab.com/profile/3318668-ecohex/)
- [SexLab Tools](https://www.loverslab.com/files/file/2018-sexlab-tools-v30/) by [Goubo](https://www.loverslab.com/profile/175859-goubo/)
- [Sexlab LightMeUp](https://www.loverslab.com/files/file/8275-sexlab-lightmeup/) by [Yinkle](https://www.loverslab.com/profile/2924493-yinkle/)

### Nomkaz

You may have seen his name pop up a few hundred times when browsing the [Skyrim: Special Edition](https://www.loverslab.com/files/category/163-skyrim-special-edition/) category on LoversLab. This dude converted everything. Check his profile and leave a nice comment for all his work!

- [LL Profile](https://www.loverslab.com/profile/2695162-nomkaz/)
- [Patreon](https://www.patreon.com/nomkazsskyrimsemods)

## SFW Mods

I'm just going to touch on these since most of them are in other lists (particularly Lexy's), so many people will already be familiar with them.

### Dragons

The familiar combo of _Deadly Dragons + Diverse Dragons + Dragon Variants_ is in here, with all that entails. It's rather difficult if you're used to the boring dragons from vanilla Skyrim because now they shoot fireballs and rain them from the sky among loads of other things, so if you're new to this setup get ready.

### Animals

I have included [Animallica](https://www.nexusmods.com/skyrimspecialedition/mods/20456) for greater variety in taxidermy targets because the same old wolves get boring fast and Immersive Creatures has crashing issues on a lot of setups. There's a bit of an incompatibility with MNC if you're on Kinky but I think the added variety is worth it as I rarely play with that mod. 

### Followers

I use [Nether's Follower Framework](https://www.nexusmods.com/skyrimspecialedition/mods/18076) to allow for up to 100 followers or summoned NPC's (but realistically you'll have to keep it to six or fewer). Most of the options are self-explanatory but if you want then to join you at your level and gain them when you do, you can open the console, click on them, and enter the command "bat nfflevel"

### Transformations

My chosen vampire mod is Enai's [Sacrosanct](https://www.nexusmods.com/skyrimspecialedition/mods/3928) because it's the most compatible, but for werewolves I use the old standby [Moonlight Tales](https://www.nexusmods.com/skyrim/mods/35470). Both are a bit overpowered in this setup but you can tweak the MCMs if you find things getting too easy.

## (MORE TO BE ADDED LATER)
 
##  Female Bodies And Armors

I'm guessing you came here to appreciate the female form. This Modlist offers two options for that. 

### "BodyGen4"

The "Default" option is a series of procedurally generated body proportions for every person in the game based on their race. For example, elves will tend to be more petite, whereas orcs will tend to be more voluptuous. If you wish to use this option, download _BodySlide.Output.7z_ from <a href="https://github.com/cacophony-wj/BS.for.LeS/">here</a> and extract it to your _LeS Directory/mods/BodySlide Output/_ folder. When finished, it should contain a folder named _meshes_ with about a dozen other folders inside. These bodies and armors will look funky without BodyGen enabled, so you will have to follow the steps below if you don't wish to use that feature. Also, please note that this means your body will be an incredibly dull default CBBE body until customized via _3BBB Morphs_ in RaceMenu. You will have to do this every time you start a new game. In addition, body morphs are not as responsive with _BodyGen_ enabled. If you don't see a change, give it a second or two. Finally, not all of the _3BBB Morphs_ do something, or at least that I can determine. You'll just have to deal with this.

### Running BodySlide

If you want to generate your own bodies, **first of all** you need to disable **_BodyGen4_** in the left pane or things will get _really_ weird.

you will also have to follow all of the steps below.

1. **MAKE CERTAIN YOU ARE ON LIGHT BUT KINKY.** Doing so with ensure that all armors for both profiles will be built in one go.
2. Launch _BodySlide x64_ from the _Executables_ menu on the right, the one with the **Run** button. 
3. You **may** receive a warning that you do not have "write access to the game data directory." This warning cannot be prevented as everyone uses different hard drives and different install directories. Follow the steps below and it will correct itself. **If you do not get this error** it means that there is a Skyrim data folder in the same directory as mine and you need to _make sure_ it is the correct one, so follow the directions below anyway.
4. Click the _Settings_ button in the lower right corner of _BodySlide_.	
5. Click _Browse_ next to _Game Data Path_.	
6. Select your **Data** directory within your **Skyrim Special Edition** directory.
7. Ensure that the _Preset_ is set to "3BBB HangEmHigh." If you wish to use a different one, select it from the menu or install your own.
8. Check the _Group Filter_ dropdown to ensure that it reads _3BBB_. (It's just to the left of the _Outfit Filter_ in the upper-right corner.) 
9.  If that dropdown is blank, or something else is listed there, click the small **magnifying glass** within the _Groups Filter_ dropdown.
10. Place a check in the box beside _3BBB_ (the top option).
11. Click **OK**.
12. Ensure that the checkbox _Build Morphs_ next to the _Batch Build_ button in the lower left is **enabled**.	
13. **Hold down the CTRL key** (very important) and click _Batch Build_. 
14. You will see a huge list of bodies and armors. Just click _Build_.
15. A prompt will appear asking where to put your custom-fitted armors. Make sure they go to **_LeS Directory_/mods/BodySlide Output**.
16. **Do not put your armors anywhere but _BodySlide Output_.**
17. I have combined the options greatly so nobody has to waste a lot of time in here. The only thing you need to choose is the color of hair poking out of a few helmets. If you are female, it is probably best to put your own hair color here. If you are male, it doesn't matter, but any female you encounter with one of these helmets will have the hair color you chose here.
18. Once you have all four helmets chosen, press **OK**.
19. Wait for all the outfits to be built.
20. If you have _no interest_ in the _Light But Kinky_ variant, you are now finished. Skip to the last step.
21. Click the magnifying glass next to _3BBB_.
22. Uncheck _3BBB_ at the top and check _Unassigned_ at the bottom.
23. Ensure that the checkbox _Build Morphs_ next to the _Batch Build_ button in the lower left is **enabled**.	
24. **Hold down the CTRL key** (very important) and click _Batch Build_. 
25. Right-click anywhere in the small window and choose _Select None_.
26. Scroll through the list until you find "BreastRopeExtreme01."
27. Select five entries.
28. The last one selected should be "BreastRopeWithWaistRopeExtreme02."
29. Scroll all the way to the bottom of the small window.
30. Starting at the bottom and moving up, sekect the eight entries from "ZAZGSBDoggieBelt" to "Shibari."
31. Press _Build_.
32. A prompt will appear asking where to put your custom-fitted breast ropes. Make sure they go to **_LeS Directory_/mods/BodySlide Output**.
33. **Do not put your ropes anywhere but _BodySlide Output_.**
34. The ropes should build so fast you'll hardly notice.
35. If at any point you received a message that an outfit failed to build, write down the outfit that failed, select it from the dropdown, and click the big _Build_ button in the bottom-center. Repeat for any other failed outfits until you get no errors.
36. You should now be ready to launch Skyrim with the **_RUN ME_** dropdown. Make certain to switch back to _Light But Sexy_ if that is the list you wish to play.

## A bit of a note on schlongs and strap-ons

Rather than use _SexLab_'s rather boring and badly-fitted strapon for scenes were a female is mistakenly placed in male role, an Oldrim mod called _Equippable Schlong_ has been included. To configure its appearance, follow these steps:

1. Open the inventory.
4. Click on the item _AddItemMenu_.
5. Pull out the item _AddItemMenu - Search_ (the one with the box icon, not the book icon).
6. Close and re-open the inventory.
7. Click on _AddItemMenu - Search_.
8. Type in _Schlong_ and click on _Equipable Schlong_ (yes it is misspelled).
9. If you are running _Light But Kinky_ be sure to configure _Cursed Loot_ as per the instructions first or you will cover the schlong in shame when you go naked.
10. Equip the schlong from your inventory.
11. Open the console with the _tilde_ key (`).
12. Type in _TFC_.
13. Close the console with the same key.
14. Adjust the camera with WASD + mouse to get a good view of the pelvic region, preferably from the side.
15. Open the console again.
16. Type in _showracemenu_.
17. Navigate over to _Genitals_.
18. Adjust that bad boy as you see fit.
19. Open your inventory and drop it on the ground.
20. Open the console again and type tfc a final time.

It should automatically appear when appropriate (Amorous Adventures scenes are the worst for this).

If you are male, the above steps can also be used to customize your own schlong.

## The below sections will be reworked and relocated 

##  A Note on SexLab for the Uninitiated

Skyrim was never designed to have animations injected into it. It most certainly was never intended to pair two actors in a close space and perfectly align them for a sex scene. Animators do a lot of the work, but the engine is far from ideal. On top of that, there are many poorly aligned animations out there. In any case, no matter how good your animations, you will often find problems like: people kissing the air, _parts_ not going _into_ each other, characters floating above the ground, or even more wacked-out stuff like falling into the ground, clipping into furniture, or people going invisible. Fortunately, SexLab allows you to correct _some_ of this with manual positioning for each animation. Here's how it works... the _L_ key on your keyboard moves you _forward,_ i.e. closer to your partner. _Shift-L_ moves you _backward,_ or the reverse. _;_ moves you _up_, or higher in elevation than your partner. _Shift-;_ does the reverse. Finally, _'_ moves you _Right_ compared to your partner, whereas _Shift-'_ moves you _Left_. (Or maybe the other left.) Get used to these, you'll be using them a lot.

##  Admiring Yourself

For those who want a little POV action or to play primarily in first person, _IFPV_ (Immersive First-Person View) is included. It's a little wonky, so it's disabled by default. Ensure you're in first person mode (F key by default) and press _NUMPAD 0_ to enable it. Then press the F key again and look downward. Tah-Dah! Should work tolerably well for POV scenes (maybe a bit of clipping) except for animations where the actors are _really_ close to each other. To switch to _vanilla_ first person for gameplay, hit the F key at any time. _If you are on Light but Kinky, please note issues with IFPV in the Troubleshooting section._

**You cannot switch to third person anymore without deactivating IFPV with _NUMPAD 0_!**

You can always watch a scene from an external view with SexLab's default freecam available with _NUMPAD 3_. Use the mouse to look around and WASD to move your "camera".

##  Specific to Light But Sexy

###  Defeat

Defeat is ... a little buggy, to say the least... but I have included it in _Light But Sexy_ as a potential death alternative. I have most of it disabled because it breaks too often and forces a reload. About the only thing left active in my setup is the ability to "surrender" with the _K_ key. Surrender as soon as you're outnumbered if you want a scene because the script delay can be excessive. If you want to enable more of this mod's features feel free, but be prepared for situations such as being stuck to the ground, unable to move, stuck to the ground _and_ unable to move, or unable to interact with anything or open your inventory. I will not help you resolve Defeat's issues.

##  Specific to Light But Kinky

###  Cursed Loot

The thing you have to remember about _Cursed Loot_ is that, once its in your modlist, your game is no longer about Skyrim and it is now about Cursed Loot. It does everything from overhauling loot, to adding followers, to changing combat and buffs, to prostitution, to prison overhaul, to death alternatives. It even has an alternate start and other quests to help you get a feel for how the mod works. A rather lenient preset is enabled for infrequent, mild encounters with bondage gear that's relatively easy to escape from until you hit level 20 where things start getting a bit more hardcore. The key "mechanic" of this mod (such as it is) is that you keep your arousal down via sexual acts to prevent "cursed traps" from triggering that lock you into bondage gear, make you more aroused, spiraling down into a self-defeating loop. One tip that people often miss: lucky charms against curses, bondage keys and sex-related potions are almost always hidden in flowers, plants, and bushes for some weird reason. (I guess that's where all the creeps hide to watch the women in Iron Pasties.) For more details I suggest you do a little searching on LoversLab.com for the Cursed Loot landing page and read up on it. It shouldn't be difficult to find, it's about the most popular mod there.

## Best Save Practices: READ ME!

Heavily modded Skyrim setups can result in save corruption in the best of circumstances. It is not likely but it is possible, and considering this might result in a save that can never be loaded again, highly undesirable. This likelihood is increased now that Wabbajack is introducing _Lover's Lab_ mods into the mix, which are notorious for resource-heavy cloak scripting, inappropriately terminated scripts that persist on the save file, and other issues. That is why I must **insist** that you follow _Wabbajack Official Save Diligence_ while playing this modlist. _If you die_ while playing, _do not allow the game to load you into the same cell (dungeon, cave, region) that you died in._ There are three ways to prevent this. 

1. All autosaving is disabled by default. Save every time you are about to pass through a door requiring a load screen where you might die. If you meet your end, load the save before you entered. Only complete zones from "bonfire to bonfire" (load screen to load screen) like this, and this way you will avoid the possibility of save corruption.
2. Save as much as you like, but after every death, completely exit Skyrim to the desktop and launch the game again to continue. This is the most recommended but also most annoying option considering how long a Skyrim with 400 mods takes to boot up.
3. If in large exterior areas like Tamriel, only save every five to ten minutes or before entering an interior zone to ensure you cross a full cell before saving. Only load saves made at these intervals.
4. **The most important thing to remember is that you can NOT "save scum" (load and save, load and save, seconds apart to get the best result) like you can in an unmodded game.** You will almost guarantee crashing and/or save corruption if you do this.

I experimented with alternate autosave systems to prevent all these headaches, but found several instances where they saved the game right at the beginning or during unavoidable SexLab scenes, such that when reloaded, an immediate crash was the only result. This is just as bad as a corrupt save, in my opinion, so I have ceased the experimentation. **Don't Get Me Wrong** SSSO would be a beautiful mod in this list were it not for _SexLab_'s quirks. If save corruption develops into a more serious issue I may explore respawn possibilities for LeS.

## A word about ENBs

The weather and lighting mods I have in this list look best with _Silent Horizons_, and I have tried almost a dozen of them. But, some people may feel its too vibrant, bloomy, or cartoony, so feel free to swap out as you see fit, but keep in mind these notes and warnings:

_Re-Engaged_ is probably the best runner-up because it has the best overall "realistic" look but I like things a little more vibrant.
_Hardlandson's_ is a great third choice with fantastic interiors and atmospheric fogs. Personally I think the exteriors are a little too washed out.
_lJoss_ is great performance wise but even more terrible about vibrance than Silent Horizons: almost looks like watercolor with this list.
_PI-CHO_ looks great for character close-ups and resembles Silent Horizons for everything else, but glare and shine in wet or rainy areas almost looks like fireworks.
_Rudy_ will technically work but is not recommended as it has no variant which supports Cathedral Weathers.
_Serio_ is probably the best ENB for customizing the Cathedral imagespaces with the MCM but comes off _far_ too bright for this list.

The other ENB's seemed either so inferior or were completely incompatible that I didn't mention them. I also left out any ENB preset that hasn't updated in over six months, since at least the "wet" shader effect was added to the binaries.

##  Adding Followers, Outfits, and Other Mods

This is not "officially" supported as per _Wabbajack Rule 11_. That said, I know you want to do it anyway, so I will offer this instruction.

**Screen Archery** by adding _Poser Mods_ is not supported. Download the _Cupid_ modlist for this purpose.

For _Gear_ it's as simple as adding it under _Added Mods_ and above _BodySlide Output - LEAVE HERE AT THE END_ in the left pane and the very bottom in the right pane. If your gear mod does something crazy like add a huge museum of displays or put in chests for you to find you might have some issues. Otherwise, just use _AddItemMenuPackSE_ (in your inventory by default) to search for the item by name and put it in your inventory. _AddItem_ is the ultimate cheat, by the way, so don't use it if you want to play the "game" part of the game. I leave it in because this list is mostly sexy people and I want players to look good exactly the way they want.

For _Follower Mods_ add them and enable them under _Added Mods_ and above _BodySlide Output - LEAVE HERE AT THE END_ in the left pane and just above _DynDOLOD_ in the right pane. If they have a lot of custom scripting (Lucien and Inigo are especially guilty of this), you will have to craft an _NFF Ignore Token_ and equip it on them after you recruit them. Be sure _not_ to "Import" *any* followers into the _Framework_ or everything will break. Also, do not recruit *any* followers that do not have a default menu option to do so. If you are unsure about your follower, read its description page and all compatibility notes for any problems with "Nether Follower Framework." If any are mentioned, you will probably need an Ignore Token. If your follower mod contains any _world or cell edits_ (changes to game spaces handled in my modlist), there may be more severe conflicts. This usually only happens if the Follower has quests to go along with them. No way to know for sure unless you "filter for conflicts" with _SSEEdit._

Finally, there is a reason I didn't pile this list with the "Greatest Hits of _Lover's Lab_". Most _Lover's Lab_ mods feature extensive scripting which conflicts with other mods, adds a large burden to Papyrus (Skyrim's rather inefficient scripting engine), or both. Mods that constantly scan for changes in the player, other people, or creatures are especially bad for _cloak scripts_ that never terminate. This includes mods that let your hair grow, your boobs get full of milk, or god forbid give every woman in Tamriel a menstrual cycle. I do not and can not support the addition of these mods. If you want them, play with them until they break and start the game over from a pre-configured save in the cell. I can almost guarantee that they will break unless you are extremely conservative. To solve all these issues would require knowledge of Papyrus coding which I do not possess. 

It might be possible to squeeze in a greater amount of such mods on a more barebones version of Skyrim. If so, I invite you to download a simple "base" list from **#unofficial-modlist-submissions** to ensure you have critical fixes and then build your list up from scratch. You can always drop by **#NSFW-mod-discussion** to compare experiences.

Before asking about adding a mod, read the list below. I **will not** help you add any of these to _Licentia et Servitium_ or any other list. And I hate to say it but I can almost guarantee significant difficulties if you try to use more than one of them at a time. I am not saying they are "bad" mods, just that they are difficult to implement or maybe just incompatible with my setup. 

	- Dripping When Aroused
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
	- Spank That Ass SE
	- The Milk Maid SE
	- The Sisterhood of Dibella

**The above list is incomplete.** I will also not support or convert any mods listed as _unstable, beta, or uncoverted_ on _Lover's Lab_. This includes a few big ones like Sanguine's Debauchery and Slaverun Reloaded. For a full list of converted and unconverted mods, check the _Conversion Tracking_ pin in **#NSFW-mod-discussion**.

All that said, if you can't figure out a mod on your own that I did not mention above, I may help you work it in on a case-by-case basis depending on how busy I am. It is expected that you have familiarity with Mod Organizer 2, xEdit, FNIS, Nemesis, and a touch of conflict resolution before you try to do anything beyond basic outfit additions.

# A bit of a note on System Settings: IMPORTANT!

I have had users experience incidents where my Skyrim default settings were not being installed upon the completion of _Wabbajack._ Before continuing, ensure that under the _System Menu_ (ESC) the following options are chosen.

## Settings 

### Gameplay

Everything here should be **UNCHECKED** except for _Show Floating Markers_. Difficulty is recommended at _Expert_, but is ultimately up to you.

### Display

_Depth of Field_ should be all the way to the left.

## Controls

These are all to your liking, except for _Quicksave_ which should be set to _F9_, and _Quickload_ which should be set to _F10_. Don't worry about using them becuase _Engine Fixes_ converts them to full saves.

## Game MCM Options

**NOTE:** Any menus or options not specifically mentioned here can be ignored.

It is _very important_ to **wait** until _all_ messages have both ceased appearing and disappearing in the upper left corner of the screen before continuing.

### SexLab

#### Install

Under **SexLab 1.63 SE dev beta 8 by Ashal@LoversLab.com**

Click _INSTALL/UPDATE SEXLAB 163 SE DEV BETA 8_

Close the menu and wait. Once again, a series of messages will appear in the upper left corner. 

Do not touch the mouse or keyboard until the following message appears:

**SexLab - SexLab v1.63 SE dev beta 8 - Ready!**

Then open the MCM and continue.

####  Rebuild & Clean

Just below **Debug / Development Mode** in the upper right corner, click _Import Settings: Click Here_

A message will appear which concludes with "Do you want to continue?" Click _Accept_

Another message will appear, "SexLab configuration successfully imported." Click _Accept_

Finally, under **Available Strap-ons** near the lower left you will see _Calyps Strapon REMOVE_. Click this option and wait for it to disappear from the list of strap-ons.

If _Light But Kinky_ is the active profile, navigate to

#### Animation Settings

And click _Allow creature animation_ in the upper right. Close the MCM and wait until a message stating **SexLab Creature Animations Installed** appears **twice**.

Creature animations **will not work** for the _Light But Sexy_ profile. Do not attempt it.

Finally, _SexLab_ is configured so that opposite-sex characters cause you to become aroused by default. If you wish to change this, reopen the MCM and navigate to

#### Sex Diary

Under **Sexual stats** on the right, click _Sexuality_ until your preference (Bisexual, Homosexual or Lesbian) appears.

### SAVE AND LOAD!

Lover's Lab recommends saving and loading the game immediately after fully configuring SexLab. Please do so now. If the QuickSave and QuickLoad buttons have changed, recall that they are now _F9_ and _F10_.

###  SL Anim Loader

####  General Options

Click _Enable All: Click Here_

Click _Register Animations: Click Here_

Wait for the **Registered _X_ new animations** message (the number varies for each profile). Be patient, it can take up to five minutes.

###  A Matter of Time

####  Presets

Click _User Settings: Load User Settings_

Answer with _Accept_ and wait for the message **The configuration was loaded successfully.**

### AGO

#### Settings

Disable _Persistent Arrows_

### Cathedral Weather

#### Settings

Disable _Configuration Spell_

###  CGO

#### Settings

_Unlocked Grip_

Click on _ESC_ next to _Hotkey_ and press the _Shift_ key.

Uncheck _Sweeping 2H Hitboxes_

Uncheck _NPCs Change Grip_

Uncheck _Skill Matches Grip_

Set **Stationary Speed Boost** to _0%_

_Dual Wield Blocking_

Click on _ESC_ next to _Hotkey_ and click down on your mouse wheel (should say _M3_ after this)

_Dodge Roll_

Uncheck _Enable iFrames_

Uncheck _NPCs Dodge_

_Leaning_

I prefer the _procedural leaning_ and _camera movement_ at X1.00, but it disagrees with many players' sense of style or their stomachs.

To ensure this doesn't happen for any other users, I recommend the following values:

**Lean Multiplier (1st Person)**: _X0.25_

**Lean Multiplier (3rd Person)**: _X0.25_

_Camera Noise_

**Camera Noise Mult (1st Person)**: _X0.25_

### Cursed Loot

**Only available with _Light But Kinky_.**

#### Debug

Click _Import Settings - USE_ and upon viewing the message asking **Are you sure?** click _Accept_

### Deadly Dragons

#### Dragons

_Special_

Uncheck _Knockdown_

### Devious Devices Helpers

**Only available with _Light But Kinky_.**

#### Basic Settings

_Where follower may ask to tie player_

Uncheck _Shops_

Uncheck _Other Dwellings_

###  Extended UI

#### Stats Menu

Check _Hide Legendary UI elements, Show attribute modifiers,_ and _Show skill modifiers_.

###  Follower Framework

####  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

Familiarize yourself with the keys under this menu's header labeled **Hotkeyed Abilities**.

### GIST Soul Trap

#### Main

_Notifications_

Enable _Show message on soul trapped_

#### Leveling

Check _Enable Leveling System_

For the skill, select _Enchanting_

### LOTD Settings

This is primarily intended for moments in _Light But Kinky_ when you can't Fast Travel.

#### General

_Shipment Crate Locations_

Enable _Carriages_

Enable _Inns_

Enable _Player Homes_

### Moonlight Tales

#### Tools

_General_

Uncheck _Transform Back Stagger_

_Apperance_

Select _Alpha (Black with Red Eyes)_

_Lunar Transformations_

Click _SKINWALKER (MEDIUM CHANCE)_ and change it to _Full Moon Fever (Full Moon Only)_

###  Quick Light

_Brightness: Wide_

_Light Key: NUMPAD 1_

Uncheck _Enable to Long press activation key_

### Sacrosanct Vampires

#### Vampire Spells, Powers and Abilities

Click _Fortitude: Disable_

###  SexLab Aroused

#### Settings

_General_

Check _Purge Dead Actors Every 10 Game Days_

Check _Enable SOS_.

###  SexLab Eager NPCs

**Only available with _Light But Sexy_.**

####  General

Click _Enable and load profile - (CLICK)_. 

Upon receiving the message **Profile loaded successfully!** click _OK_ and close the MCM.

You'll be having a _lot_ of sex on the installed profile. If that bothers you, come back to this menu and tinker with the options until you get something you like.

This mod takes a bit to activate. 

Wait for two messages to appear in the upper left: **Mounted Exposure (SLEN) added** and **Masturbate (SLEN) added**.

###  SexLab Solutions

**Only available with _Light But Sexy_.**

####  follower

Choose the appropriate options here to offer a follower instead of yourself for sexual favors. This is mainly useful if you aren't attracted to a particular sex.

####  Miscellaneous

_Integration_

Click _SLEN integration_

### SexLab Tools

#### Settings

_Matchmaker queue_

**Matchmaker queue key**: set to _NUMPAD 2_

Ignore the message that the key is already mapped and answer "Yes."

**Please Note**: You can hover your crosshair over any actor and press _NUMPAD 2_ to set up a sex scene. While a scene is running, you can press the _H_ key to select from a list of available scenes.

###  Sky UI

####  General

_Item List_

**Font Size**: _Small_

_Active EFfects HUD_

Uncheck _Enabled_

####  Controls

**First ensure that you have configured QuickSave to F9 and Quickload to F10 or you will lose all your work so far.**

Set the first four **Favorite Groups** to _F5 - F8_ to avoid a conflict with follower commands. 

###  SLA Monitor Widget

####  Scanner Settings

Customize the scanner to your taste. It will tell you who (or what) is horny and how greatly. If you are only interested in females, choose that option. If you are only interested in humanoids, choose that option. It's up to you.

I must insist that you set **Interval** of no lower than _60_ and a **Range** of no greater than _1024_.

#### Widget Looks

Click _Vertical Anchor - Top_ and change it to _Center_

Click _Font Size - 12 PTS._ and increase it to _16_

###  Storm Lightning

####  Presets

Choose _Ultra Realistic_ and wait for it to say **DONE**

#### Advanced

Check _Compatibility Mode_

### Summermyst Enchantments

Check _Enable Fortify Skill Caps_

###  Trade & Barter

####  Barter Rates

_Settings_

Enable _Modify Barter Settings_

_Presets_

Select _Barter Presets: Medium_

### Ultimate Combat

#### General

_Game Balance Settings_

Disable _Speed Bonus_

_Others_

Disable _Swing Effect_

_Locational Damage_

Increase _Headshot Damage Mult_ to _2.0_

#### NPC Setting

_NPC_

Select _Dodge: Disable_

### Wildcat Combat

#### Stamina Costs

Check _Disable Pulled/Held Bow Stamina Cost_

Scroll down to the bottom.

#### Injuries

Check _Switch to Burst Injuries_

#### Timed Block

Check _Disable Timed Block_

#### difficulty

Check _Allow Wildcat to Manage Difficulty_

### XPMSE

Check _Disable Style Cloak Spell_

###  ZaZ Animation Pack

**Only available with _Light But Kinky_.**

####  SexLab

When first clicking this menu, it may appear to be stuck. It takes about a minute to show any visible change. Just wait. 

**SexLab Animations**: Click the grayed out word _Register_ and wait 30 - 60 seconds until the greyed out word _Registered_ appears. 

Under **Animation**, uncheck _Override_ as Devious already handles this function.

###  Defeat

**Only available with _Light But Sexy_.**

Please ensure that you have configured every other MCM before this one.

Then save and load your game.

This is in case you need to change settings upon a restart, because Defeat must always be configured _last_.

####  General Settings

Click _Mod Status - DISABLED_

Upon receiving the message **Installing... you must close the menu and wait until you see the notification.** click _Accept_

Close the MCM and wait for the message **Defeat: Installed**. 

Re-open.

Next, click _Import Settings_ on the right.

## All done!

There you go, fellow deviant. Be sure to press **F9** for a last second save in case spawning into Skyrim prompts a crash (which has been known to happen, it helps if you give it a minute before trying). Talk to the Mara statue to begin your journey. If you are on _Light But Sexy_, I recommend one of the _Something Sexy_ starts (dropped nude into a sticky situation) and if you are on _Light But Kinky_, I recommend the _Sex Slave_ start for a good look into how _Cursed Loot_ works. Spoiler though, there is no sex, just lots of bouncy-boobed slow-walking in bondage gear.

##  Troubleshooting

###  What are all these Form 43 warnings? I thought Form 43 was bad news. 

In the normal modding world this would be true, but this is Lover's Lab, which is notoriously resistant to change. Some of the mods have issues if they are converted. So **do not attempt to convert the Form 43 plugins into form 44**! These are left this way intentionally. I can't stop MO2 from warning you about them but I can strongly insist that you not act on those warnings.

### Why are there so many duplicated animation folders? _or_ Why do I have to CTRL-CLICK to build _BodySlide_?

_Mod Organizer 2_ does not put edits to existing files in the _overwrite_ folder, only newly created files. _CBBE_, _3BBB_ and _BD_ come with "default" meshes that will be changed by _BodySlide_ if you do not direct them to the proper directory yourself. Likewise, _Nemesis_ edits all the animation source files when it updates instead of putting the changes in the overwrite folder. If you don't believe me, I encourage you to check _MO2_'s documentation or the _Nemesis_ closed _Issues_ section on Github. If this doesn't convince you, I encourage you to test it yourself.

### I tried to wear a piece of gear but my body disappeared!

The _Devious_ equipment is invisible unless _BodySlide_ is fully run. Follow all the steps in the _BodySlide_ section.

###  My skin pokes through my armor! or My bald head pokes through my hood!

Particularly voluptuous (thicc) BodySlide presets will cause clipping (skin poking through clothing) on some outfit variants that are skintight. This may include randomized women from BodyGen. Nothing can be done about this so either ignore it or generate everyone with a more subdued BodySlide preset. 

There are also issues with some hoods causing bald heads to poke through that I have yet to resolve. This mostly happens when the PC wears a hooded robe and crouches, so if it bothers you, don't do either of those things.

### Some of me is too _jiggly_! (Especially the belly.)

I tried to minimize it as much as possible, but the available CBPC presets are kinda not ideal. Either reinstall the _CBBE 3BBB_ mod (position 256) and experiment with the CBPC options or install _Sinful CBPC_ (Google it) for fine control. Load order shouldn't matter, but if the MCM won't appear, open the console and type _setstage ski_configmanagerinstance 1_ and wait for the message(s).

### I read a skill book but my skill didn't go up!

This is because you "can't concentrate" if you're horny, so you don't get 100% skill experience from skill books. Check the _Magic Effects_ tab of your _Magic_ window for **red** effects that affect experience gain. Usually they are marked **Lover's Desire**. If you're not locked up with something, alleviate that need and then read the book. If you're locked into gear and can't _take care of business_, you're out of luck. Leave the book where it is and read the next one you come across, otherwise it will be wasted.

### I'm running _Light But Kinky_ and I can't find my save!

Try using _Show All Saves._ Devious or Cursed Loot (one of the two) sometimes puts them in a weird place, most likely because of legacy scripts.

### The head bob is making me sick! I want to turn it off!

Untick _Immersive First Person View_ in the left pane, then go into the MCM for _CGO_ and set _Camera Noise Mult (1st Person)_ to 0.00.

### CGO isn't leaning / dodging! _or_ When I go into an adult scene, I hear sounds and voices but they just stand there!

I sometimes forget to run _Nemesis_ before uploading a build. Make a comment in Discord and I'll get to it when possible.

###  I did all that but the things are still just standing there, especially when I get assaulted.

_Skyrim Special Edition_ is not well supported by the _Lover's Lab_ community, or at least not as robustly. Most players seeking to use such content do so on _Oldrim_ or _Legendary Edition,_ which unfortunately suffers from an inferior engine as far as stability and memory management goes. _Legendary Edition_ is also not "officially" available on _Steam_ any longer, which discourages mainstream mod (and modlist) authors from supporting it. 

As such, animations triggered from the SE versions of _Defeat_ and _Cursed Loot_ seem to be called in a slightly different fashion than those from _SL Tools_, _SL Solutions_, or _SLEN_. They suffer from intolerable script lag at times, regardless of how many mods or animations are installed. I understand it's a known issue that is being worked on, but until it is resolved, you'll have to break your immersion a bit. If an animation seems stuck **and** there are no moans of pleasure, just various breathing and grunts (or silence), open the console with the tilde key (`), wait for all messages to cycle, then close the console again. You may have to repeat this process at least once.

### My arms won't go into a binder _or_ my hands are floating outside of my bindings _or_ my gag won't go in my mouth _or_ one of these is true for an NPC.

First, if you added something, remove it or rerun _Wabbajack._ If you didn't add anything, there's not much I can do. _Devious_ handling of these matters is extremely finicky in its original version on Oldrim and even more so for Special Edition. Facial Expressions in Special Edition have always been a problem and the NPC arm / invisible hands problem persists to this day no matter which version you use. If you want a more bug-free game, don't use _Devious Devices_ because this is **way** out of Skyrim's purview.

###  I'm locked into some gear and I can't move in third person.

_Devious Devices_ doesn't like the SE version of _Immersive First Persion View_ very much. Don't disable IFPV after enabling it or you will get this bug every time you stop moving while in restrictive gear. If you were unaware of this fact, save your game, reload, and the problem should go away. Don't enable _Immersive First Person View_ while locked up unless you plan to stay in first person.

### I'm playing _Light But Kinky_ and I'm in such an incredible amount of bondage gear that I can't do anything at all!

Time to reload a save before you got into that situation. Seriously, if there were an option to prevent nested equipping of Devious Devices I would enable it. But there isn't. Not without disabling most of the hilariously meme-worthy scenarios. If you get equipped in anything extremely punishing, I recommend reloading your game if anything else really punishing gets equipped on you. Unless you just want to see how ridiculous things can get.

### I want creatures in _Light But Sexy_!

Thanks to a helpful user an easy way to accomplish this has been discovered and tested. Enable _only_ the creature animations in the **INTENTIONALLY DISABLED** section, move them with the other _SexLab Animations_, and re-run _Nemesis Behavioral Engine_ from the dropdown. Ensure that all four menu options remain checked. Do _not_ reinstall any of the animation packs, or add your own, as the end result will probably be frozen animations (aka the T-Pose). Ensure that no new ESPs are enabled at the bottom of the right pane.

### Stuff is disabled. Did you forget? Or, can I enable it all, for the best of both worlds?

No. All that stuff is disabled on purpose. Most of it is for technical reasons. For example, _Cursed Loot_ shuts down all of _Eager NPCs_ functions, even if you disable _Cursed Loot_, so the two won't work together. This being the biggest way to experience consequence-free romance, I left the other "free love" mods disabled for roleplay reasons, since _Light But Kinky_ is supposed to be a harsh, punishing world. If you really want more options in _Light But Kinky_, these mods are _okay_ to enable, but don't fit the theme:

- Amorous Adventures Extended SSE v1.2.3
- SexLab Solutions v3 - Revisited SE v1.1.5

Just tick them in the left pane, move them under "SexLab Quests", and move the ESPs that showed up at the bottom of the right pane somewhere with the rest of the SexLab stuff. It shouldn't matter too much where since none of them conflict with anything. _Do not_ enable anything else because it all conflicts even though multiple support threads might assure you it doesn't. For example, _Defeat_ does not recognize equipped devices, so you can totally be taken advantage of straight through chastity gear in a full set.

As far as enabling stuff in _Light But Sexy_... _don't try it._ None of the Devious stuff will work because of the reasons above.

## Gameplay Tips - Walkthroughs - Light Spoilers for the Hopelessly Stuck.

### I was locked up in the "princess" start and something defeated me and I got teleported somewhere and the quest was completely broken! This isn't fair!

Life isn't fair and _Cursed Loot_ doubles down on that. Seriously, though, there are a couple of weird spawn areas that can be troublesome with _Animallica_ and _Immersive Patrols_. Be sure to save your game before exiting the hideout either time and hope you don't get a mob spawn nearby or at Sarethi farm.

### I can't find those damn keys in the _Light But Kinky_ "princess" start!

They are non-existent until triggered. The _hideout key_ spawns outside on a random slaver corpse after you are free from the cage. You must search every body until you find it. I will tell you that the bodies are all near the road and do not go beyond the man on the ledge on one extreme or the man in the weeds on the other, so keep checking. The _office key_ spawns when you search the body of the Slaver Boss and read the note pop-up. Search every corpse and chest in the room until you find it. If you can't find it at first, keep searching until you do. I have never had an instance where it didn't show (and I have tested it many, many, _many_ times)

### Where the hell do I go after Chloe tells me about the secret passage?

Go back out the way you came and to the cave where Ralof and Hadvar are. The main quest may break if you go through _Cursed Loot's_ "narrow passage" shortcut and the _Unofficial Patch_ makes sure to warn you about it, so I have removed that option. Go all the way back in the cave until you get to the room with the spiders, kill them (or let Chloe do it, she's a beast) and search the Imperials in there for a _Torn Note_. Read the note.

### I was bound and then defeated and then teleported somewhere and now I can't get up from the ground!

Wait 30 seconds, save, wait 30 more seconds, reload the save you just made. If this doesn't allow you to stand up, you'll have to load a game from before you were defeated.

## Removing the Modlist

You can just remove the _LeS_ folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Contact

I am regularly available on the [Wabbajack Discord](https://discord.gg/wabbajack) (`#nsfw-mod-discussion`) (`#licentia-et-servitium-support).

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
