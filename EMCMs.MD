- [Evanescentium Configuration](#evanescentium-configuration)
- [A Note About the tamer BodySlides](#a-note-about-the-tamer-bodyslides)
- [Setting your resolution](#setting-your-resolution)
- [Character Creation](#character-creation)
- [A bit of a note on System Settings](#a-bit-of-a-note-on-system-settings)
  - [Controls](#controls)
- [CONTROLLER MAPPING](#controller-mapping)
- [Game MCM Options](#game-mcm-options)
  - [SexLab](#sexlab)
    - [Install](#install)
  - [SexLab](#sexlab-1)
    - [Rebuild & Clean](#rebuild--clean)
  - [SexLab](#sexlab-2)
  - [SAVE AND LOAD!](#save-and-load)
  - [A Matter of Time](#a-matter-of-time)
    - [Presets](#presets)
  - [Ashes](#ashes)
    - [MAIN](#main)
  - [BBLS](#bbls)
    - [Resource Heavy](#resource-heavy)
  - [CBBE 3BBB Addon](#cbbe-3bbb-addon)
  - [CGO](#cgo)
    - [Settings](#settings)
  - [FG Animation Selector](#fg-animation-selector)
  - [FlowerGirls SE](#flowergirls-se)
  - [Follower Framework](#follower-framework)
    - [System](#system)
  - [Immersive Creatures](#immersive-creatures)
    - [Creature Toggles](#creature-toggles)
    - [Additional Spawns](#additional-spawns)
    - [Night Spawns](#night-spawns)
  - [OStim](#ostim)
    - [Sex scenes](#sex-scenes)
  - [Serio's Hotkeys](#serios-hotkeys)
  - [SmoothCam](#smoothcam)
    - [Presets](#presets-1)
  - [Storm Lightning](#storm-lightning)
    - [presets](#presets-2)
  - [The Ultimate Dodge Mod](#the-ultimate-dodge-mod)
    - [NPC Settings](#npc-settings)
  - [Trade and Barter](#trade-and-barter)
    - [Barter Rates](#barter-rates)
  - [VioLens](#violens)
    - [Profile System](#profile-system)
- [All done!](#all-done)
  
## Evanescentium Configuration

## A Note About the tamer BodySlides

_Evanescentium_ offers a "less overtly slutty" look for the female NPCs of Skyrim. Assuming you _do not_ build the BodySlides under _any_ of the other profiles, and build them under _Evanascentium_ instead, as always following _all_ of the instructions in **BODYSLIDE.md**, the female characters will wear much more modest clothing for walking around -- ideal if you're playing in mixed company (heaven forfend) or if seeing women with their lady meat dangling out makes you feel like a major dingus. Bear that in mind as we go along: if you want slutty outfits, build BodySlides under _Licentia_ (or another profile); if you do not want slutty outfits, build them under _Evanescentium_. (You will have to delete them if you already built them under the wrong profile. Again, they are in _Licentia/mods/BodySlide Output_)

## Setting your resolution

_Evanescentium_ should default to _1080p_ resolution, _regardless of your desktop resolution._ This is because after much testing I have found this to be the smoothest profile for both graphical and Papyrus performance. If you wish to increase it, bear in mind that you _will not_ get 60FPS at 4k and most likely not at 1440p. To do so, click the hammer and gear icon and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. (Should be under [Display] which is itself in alphabetical order.) Change the values for _iSize H_ and _iSize W_ to the resolution you wish. Below are some common resolutions you can use.

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/1778). Install it as you would any other Mod Organizer mod. Just put it under _Added Mods._

I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard).  There are no presets for Argonians and Khajiits for some reason. I made two male presets, a mage and a warrior, with an (M) after the name. Keep in mind that if you choose a _male elf_ character, the facial hair will look weird unless you switch the _Face Part_ to **3.** You'll know you have the right one when it says "high poly" in the bottom right and the face suddenly looks 10,000 times more detailed. Tweak to your liking, you might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Don't ask me either. Experiment and figure it out. One thing you can do is open the console with the _Tilde `_ key, click on yourself, and type _unequipall_, and then reload your preset to go nude. Click _Done_ (in the lower left) when you are finished.

**IF YOUR BODY TURNS PURPLE**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## A bit of a note on System Settings

### Controls

The controls for _Evanescentium_ are specifically designed for use with a controller. Please be certain to **delete** any _ControlMap_Custom_ files in your Skryim **game* directory if you plan to do so. Note that you will have to bind any keyboard controls again (such as QuickSave / QuickLoad)

If you want to use a mouse and keyboard, close Skryim and disable everything under the _Controller_ section in the left pane. 

Unfortunately 8-way dodges are not possible with a controller without an external program and forcing "always run" which is essential to any type of Sneak. As you play, keep in mind that you can roll or step dodge in only the four cardinal directions. Sneak / Dodge is on "B" (Like Dark Souls). You can switch between the step dodge and a roll with the G key. The menu is weird, "Start" opens the system and quest menu "RB + Start" opens the "TweeN" menu (skills / magic / items / map). Lock on is set to "LB." _CGO_ and _TUDM_ are both preconfigured. _Left_ on the D-Pad changes your weapon grip from one- to two-handed. _RB_ blocks when you are dual-wielding. _Down_ on the D-Pad enters and exits Sneak mode. _Up_ on the D-Pad turns Quick Light on and off. Keep this in mind when you choose dialog options and don't use the d-pad!

**Under the System > Settings Menu** change Quicksave_ to _F9_, and _Quickload_ to _F10_. Don't worry about using them because _Engine Fixes_ converts them to full saves. However, and I realize this is a pain, _do not_ use the "QuickSave" option from the System menu! Bad things can (and probably will) happen to your long-term save. In addition _do not_ turn on any "Autosave" options. They can and will corrupt with time. Get used to saving a lot!

I'm oldschool so sometimes I play with an inverted controller. If your controls are inverted you might have to change it since I forgot to.

## CONTROLLER MAPPING

Start: Journal
Back: Wait
LT: Left Attack
RT: Right attack
LB+Back: Quicksave
RB+Start: Tween menu (character menu)
LB+RB: Shout (in that order)
LB: Lock-on (activate / deactivate)
RB: Sprint
LS: Favorites
RS: Switch POV
A: Activate
B: Sneak (when still) / Roll (when moving)
X: Ready weapon
Y: Jump

## Game MCM Options

**NOTE:** Any menus or options not specifically mentioned here can be ignored.

It is _very important_ to **wait** until _all_ messages have both ceased appearing and disappearing in the upper left corner of the screen before continuing. 

### SexLab

SexLab is present, yes, but _only as a framework for orgasms that OSEX can use._ OSEX's orgasms are terrible... actually, they're non-existent. The bar fills. It empties. It starts filling again. Nothing about the scene changes.

With OSTIM and at least the SexLab framework (properly configured) you will at least get a decent orgasm.

#### Install

Under **SexLab 1.63 SE dev beta 8 by Ashal@LoversLab.com**

Click _INSTALL/UPDATE SEXLAB 163 SE DEV BETA 8_

Close the menu and wait. Once again, a series of messages will appear in the upper left corner. 

Do not touch the mouse or keyboard until the following message appears:

**SexLab - SexLab v1.63 SE dev beta 8 - Ready!**

Then open the MCM and continue.

### SexLab

####  Rebuild & Clean

Just below **Debug / Development Mode** in the upper right corner, click _Import Settings: Click Here_

A message will appear which concludes with "Do you want to continue?" Click _Accept_

Another message will appear, "SexLab configuration successfully imported." Click _Accept_

### SexLab

### SAVE AND LOAD!

Lover's Lab recommends saving and loading the game immediately after fully configuring SexLab. Please do so now. If the QuickSave and QuickLoad buttons have changed, recall that they are now _F9_ and _F10_.

### A Matter of Time

#### Presets

Under **User Setting** click _Load user settings - GO_ and wait for the confirmation message.

###  Ashes

#### MAIN

Under **Main Options** just click _Mod Activated_. The primary purpose of this mod is to load the game elsewhere when you die to prevent save corruption. By default, this will always be the inn in Riverwood, but you can change this by sleeping in a bed. The intention is to just reload your game after you spawn, but feel free to configure it more harshly if you wish, _Ashes_ is one of the best death mods out there and can be used for quite punishing Iron Man scenarios.

### BBLS

This is the _Luxury Suite_ and I must confess I'm not too familiar with the options just yet. Most of them seem down to sexual preference so just read the descriptions and configure as you see fit. I do recommend that under

#### Resource Heavy

You _deselect_ all of the options here to prevent compatibility issues with _Nether._

### CBBE 3BBB Addon

_OSex_ and _OStim_ will crap out if you don't change the hotkeys here. I recommend setting them to the first five function keys. Bear in mind you will need to use these instead of the NUMPAD to set people to SMP Physics, and you will not be able to use the SKYUI groups anymore.

###  CGO

#### Settings

**Leaning**

Set _1st Person_ to _0.00_ to prevent motion sickness.

**Camera Noise**

Set to _0.00_ to prevent motion sickness.

**360 Combat**

_Not supported._ Do _NOT_ enable this option.

### FG Animation Selector

Enable _Auto-show in player scenes._ Bear in mind FG is *not** friendly to POV scenes... your head will be invisible! You must switch to third person with _R3_ (or _F_) or enable freecam mode with the primary hotkey.

### FlowerGirls SE

The bread & butter. 

These here are mostly preference except for _Strap-on model_ under **Roles** which needs to be set to _CBBE_

I do recommend that you set the **Freecam** hotkey to _NUMPAD 3_ for consistency with the SexLab profile. You may need to save and reload the game a couple of this times for FG to detect PapyrusUtil and enable this option. If that doesn't work, restart FG under **Mod Options** and wait for all messages to stop.

###  Follower Framework

####  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

### Immersive Creatures

#### Creature Toggles

Disable _Goblin_

#### Additional Spawns

Disable _Animal Spawns_ and _Ore Guardian Spawns_

#### Night Spawns

Disable all these.

### OStim

This is maybe the pickiest mod in the setup, and yes, it originates from _Lover's Lab_ so that's no surprise at all.

#### Sex scenes

Enable _Clipping-less first person_, _Misalignment protection_ and _Flipped animation fix._

Everything else is personal preference.

**When you first start an OStim/OSex scene** you will be _utterly fucking lost._ Guaranteed. You will need to read the modpages for _OSex_ and _OStim_ on the Nexus to have **even the slightest** clue how to control the sex scenes with the _NUMPAD_ because it is _complex_ and there are **ZERO** onscreen instructions.

### Serio's Hotkeys

Recommend _Use Vanilla Hotkeys_ if you're on controller.

You'll have to read about the mod if you wanna use it, I don't mess with it really.

### SmoothCam

#### Presets

Click on _Slot 1: Souls-Like_ under _Load Preset_ and wait for the message.

### Storm Lightning

This profile is a bit less script heavy so you can do

#### presets

And choose _Ultra Realistic_ if you want.

### The Ultimate Dodge Mod

#### NPC Settings

I fucked up the scripts here. Until I get it figured out, you need to check and uncheck _NPC Dodge AI_. My followers have been known to get stuck in midair until this is done.

### Trade and Barter

#### Barter Rates

Enable _Modify Barter Settings._ Under "Presets" choose _Medium_.

### VioLens

#### Profile System

Load the _VioLens_ profile under settings

## All done!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. There are two options to start your game. The first is to talk to the Mara statue for a more traditional method. Sexy starts (most of the time involving you being naked) are available from the bookshelf nearby. You have to pick up the book to activate one of these, then sleep in the bed.
