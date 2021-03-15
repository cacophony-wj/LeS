- [Licentia Configuration](#licentia-configuration)
  - [Setting your resolution](#setting-your-resolution)
  - [Character Creation](#character-creation)
  - [AS SOON AS CHARACTER CREATION IS COMPLETE](#as-soon-as-character-creation-is-complete)
  - [A bit of a note on System Settings](#a-bit-of-a-note-on-system-settings)
  - [Controls](#controls)
  - [CONTROLLER MAPPING](#controller-mapping)
  - [Game MCM Options](#game-mcm-options)
  - [SexLab](#sexlab)
    - [Install](#install)
  - [SexLab](#sexlab-1)
    - [Sex Diary / Journal](#sex-diary--journal)
    - [Rebuild & Clean](#rebuild--clean)
    - [Animation Settings](#animation-settings)
    - [Animation Settings](#animation-settings-1)
  - [SexLab](#sexlab-2)
  - [SAVE AND LOAD!](#save-and-load)
  - [SL Anim Loader](#sl-anim-loader)
    - [General Options](#general-options)
  - [A Matter of Time](#a-matter-of-time)
  - [CGO](#cgo)
    - [Settings](#settings)
      - [Leaning](#leaning)
  - [Follower Framework](#follower-framework)
    - [System](#system)
  - [LOTD: The Curator's Companion](#lotd-the-curators-companion)
  - [Quick Light](#quick-light)
    - [Serio's Hotkeys](#serios-hotkeys)
    - [SexLab Aroused](#sexlab-aroused)
      - [Settings](#settings-1)
    - [SexLab Eager NPCs](#sexlab-eager-npcs)
      - [General](#general)
    - [SexLab Solutions](#sexlab-solutions)
      - [follower](#follower)
  - [SexLab Tools](#sexlab-tools)
    - [Settings](#settings-2)
  - [SKY UI](#sky-ui)
    - [General](#general-1)
  - [SmoothCam](#smoothcam)
    - [Presets](#presets)
    - [Compatibility](#compatibility)
  - [SSoB](#ssob)
  - [Storm Lightning](#storm-lightning)
    - [presets](#presets-1)
  - [Ashes](#ashes)
  - [All done!](#all-done)
- [ULTRA MEGA IMPORTANT](#ultra-mega-important)

# Licentia Configuration

## Setting your resolution

_Licentia_ has been configured to run at _1920x1080_ by default. This not only ensures higher FPS, but also quick turnaround for the various "animations" which are laggy in the best of situations. If you wish to change this to a higher resolution, click the hammer and gear icon and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. (Should be under [Display] which is itself in alphabetical order.) Change the values for _iSize H_ and _iSize W_ to the resolution you wish. Below are some common resolutions you can use.

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/1778). Install it as you would any other Mod Organizer mod. Just put it under _Added Mods._

I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard).  There are no presets for Argonians and Khajiits for some reason. I made two male presets, a mage and a warrior, with an (M) after the name. I also added some weird Yojimbo Dark Elf named Zet. He's marked with (M) too.

Tweak to your liking, but bear in mind that many of the close-cropped hairstyles will **NOT** look right until you select the _High Poly Head_ by navigating to the _Head_ portion of RaceMenu and choose _Face Part 3_ (near the bottom). You might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Experiment and figure it out. One thing you can do is open the console with the _Tilde `_ key, click on yourself, and type _unequipall_, and then reload your preset to go nude. Click _Done_ (in the lower left) when you are finished.

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

You will get a **POPUP** from "The Curators Companion". Answer Ok and **DO NOTHING** until you get another popup. After the second popup, you should be ready to continue.

## A bit of a note on System Settings

## Controls

The controls for "Licentia" have been set to controller by default. I'm old and don't handle buttons well. If you wish to use a controller like me, please be certain to **delete** any _ControlMap_Custom_ files in your Skryim **game* directory if you plan to do so. Note that you will have to bind any keyboard controls again (such as QuickSave / QuickLoad)

Unfortunately 8-way dodges are not possible with a controller without an external program and forcing "always run" which is murder to any type of Sneak. As you play, keep in mind that you can roll or step dodge in only the four cardinal directions. 

**Under the System > Settings Menu** change _Quicksave_ to _F9_, and _Quickload_ to _F10_. Don't worry about using them because _Engine Fixes_ converts them to full saves. 

_I've been through the turnstile and am coming at you inverted._ **So are my controls.** If you don't like an inverted up and down you may have to change it yourself.

## CONTROLLER MAPPING

- Start: Journal
- Back: Wait
- LT: Left Attack
- RT: Right attack
- LB+Back: Quicksave
- RB+Start: Tween menu (character menu)
- LB+RB: Shout (in that order, you kinda haveta roll your fingers across them)
- LB: Lock-on (activate / deactivate)
- RB: Sprint
- LS: Favorites
- RS: Switch POV
- A: Activate
- B: Roll
- X: Ready weapon
- Y: Jump
- D-Pad Up: Turn on / off Quick Light
- D-Pad Down: Sneak / Stop Sneaking
- D-Pad Left: Switch grip between 1-handed and 2-handed (CGO)
- (Yes, you will crouch up and down and turn lights on and off in dialog menus.)
- (Use the sticks instead!)

## Game MCM Options

**NOTE:** Any menus or options not specifically mentioned here can be ignored.

It is _very important_ to **wait** until _all_ messages have both ceased appearing and disappearing in the upper left corner of the screen before continuing.

## SexLab

### Install

Under **SexLab 1.63 SE dev beta 8 by Ashal@LoversLab.com**

Click _INSTALL/UPDATE SEXLAB 163 SE DEV BETA 8_

Close the menu and wait. Once again, a series of messages will appear in the upper left corner. 

Do not touch the mouse or keyboard until the following message appears:

**SexLab - SexLab v1.63 SE dev beta 8 - Ready!**

Then open the MCM and continue.

## SexLab

### Sex Diary / Journal

Your character is considered heterosexual by default. If you wish to change this, under **Sexual stats** on the right, click _Sexuality_ until your preference (Bisexual, Gay, or Lesbian) appears.

###  Rebuild & Clean

Just below **Debug / Development Mode** in the upper right corner, click _Import Settings: Click Here_

A message will appear which concludes with "Do you want to continue?" Click _Accept_

Another message will appear, "SexLab configuration successfully imported." Click _Accept_

If you do want your females to sometimes use strapons, navigate to

### Animation Settings

and click the mark on the right that reads _Females Use Strap-ons._

Note that **ALL** of _SexLab's_ original old animations have been suppressed due to unpopularity. If you want to re-enable them for some reason, click _CLEAR SUPPRESSED LIST - CLICK HERE_

### Animation Settings

**Creature animations are not included.** If you wish a heavier Lover's Lab modlist featuring creatures, "Devious" content (if you don't know, you don't need to know), and more of an emphasis on smut, try the _Dungeons & Deviousness_ modlist.

## SexLab

## SAVE AND LOAD!

Lover's Lab recommends saving and loading the game immediately after fully configuring SexLab. Please do so now. If the QuickSave and QuickLoad buttons have changed, recall that they are now _F9_ and _F10_.

##  SL Anim Loader

### General Options

Click _Enable All: Click Here_

Click _Register Animations_

The process will take about two minutes, whereupon you will receive a message that animations have been registered. Just click _Accept_

## A Matter of Time

Load the User Preset.

##  CGO

### Settings

#### Leaning

**I recommend the following values:**

_Lean Multiplier (1st Person)_: _X0.00_

_Lean Multiplier (3rd Person)_: _X0.25_

_Camera Noise_

_Camera Noise Mult (1st Person)_: _X0.00_

Scroll all the way down.

##  Follower Framework

###  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

## LOTD: The Curator's Companion

Some users have reported excessive lag with occasional inventory scans of the Dragonborn Museum when reaching near-capacity (over 1,000 displays and over 100 hours of gameplay)

If this sounds like you, navigate to the _MoreHUD & Scan_ portion of this MCM and set "Museum Scan Interval (Minutes)" to _120_.

## Quick Light

This is automatically set to "up" on the D-Pad, even though it says NUMPAD 1. Set it to whatever you wish. All it does is turn on a light so you can see around you.

### Serio's Hotkeys

Recommend _Use Vanilla Hotkeys_ if you're on controller.

You'll have to read about the mod if you wanna use it, I'm still experimenting. Basically you can set it so your hotkeys are a function of shoulder button + face button for a total of 16 hotkeys on the controller (kinda like FF14 if you've ever played that on console)

###  SexLab Aroused

#### Settings

_General_

On the right, import the profile.

###  SexLab Eager NPCs

####  General

Decide if you want a lot of automatic prompts for sex or a few.

If you want a few, click _Enable and Load Defaults - (CLICK)_.

If you want a lot, click _Enable and load profile - (CLICK)_. 

Upon receiving the message **Profile loaded successfully!** click _OK_ and close the MCM.

This mod takes a bit to activate. 

Wait for this message to appear in the upper left: **Masturbate (SLEN) added**.

###  SexLab Solutions

####  follower

Choose the appropriate options here to offer a follower instead of yourself for sexual favors. This is mainly useful if you aren't attracted to a particular sex.

## SexLab Tools

### Settings

_Matchmaker queue_

**Matchmaker queue key**: set to _NUMPAD 2_

Ignore the message that the key is already mapped and answer "Yes."

**Please Note**: You can hover your crosshair over any person and press _NUMPAD 2_ to set up a sex scene at any time with any animation without any consequences. Please note that the person in the _receiver_ slot is always the "bottom" in a sex scene. Every other slot is an _actor_ and will primarily have sex with the receiver although sometimes it varies. 

To add yourself to a slot, hover your crosshair over empty space and press _NUMPAD 2_. Then select the slot you want to participate in. Each time you place somebody in a slot, you will have to choose several options. _Set with animation_ obviously, then the type of animation you want. 

Finally you'll have to type in how many total people will be in the scene. And yes, you have to do this _every time you add somebody_. It's not the best. 

Here's what makes up for it though, after you begin the scene by clicking on empty space and choosing _Begin scene_, you can press the _Shift+H_ keys to select from a list of commands, including changing positions, stages, and choosing animations from a list. Remember, it only draws from the first 250, or the first 250 of whatever tag you set. If your tag is too specific, nothing will be in the list.

## SKY UI

### General

Set _Font Size_ to Small.

Disable the _Active Effects HUD_. (It gets in the way of my AMOT preset.)

## SmoothCam

### Presets

Click on _Slot 2: EasyEase_ under _Load Preset_ on the **RIGHT SIDE OF THE SCREEN** and wait for the message.

## Ashes

All you need to do is enable the mod.

Some people have reported corruption with the injuries module, particularly when save scumming.

If this sounds like you, you may wish to scroll down and deselect the _Simple Injuries_ checkbox.

## All done!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. There are two options to start your game. The first is to talk to the Mara statue for a more traditional method. Sexy starts (most of the time involving you being naked) are available from the bookshelf nearby.

# ULTRA MEGA IMPORTANT

**The Ultimate Dodge** will **NOT** work until you leave the starting cell after sleeping on the bed after talking to the statue or choosing a book. It will also **NOT** work **UNTIL YOU PRESS G TWICE.** The **FIRST** thing you should do as soon as you spawn is **PRESS G TWICE**. If you message me about how you are stuck in the air after a dodge, I will tell you to read this entire readme again.
