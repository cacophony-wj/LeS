- [Licentia Configuration](#licentia-configuration)
  - [Setting your resolution](#setting-your-resolution)
  - [Character Creation](#character-creation)
  - [AS SOON AS CHARACTER CREATION IS COMPLETE](#as-soon-as-character-creation-is-complete)
  - [A bit of a note on System Settings](#a-bit-of-a-note-on-system-settings)
  - [Controls](#controls)
  - [DEFAULT CONTROLS AND HOW TO CHANGE THEM](#default-controls-and-how-to-change-them)
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

Most _OStim_ functions require significant interaction with the keyboard, especially the NUMPAD, so sadly the controls for "Licentia" have been returned to mouse and keyboard by default.

**Under the System > Settings Menu** change _Quicksave_ to _F9_, and _Quickload_ to _F10_. Don't worry about using them because _Engine Fixes_ converts them to full saves. 

To change the _Quick Light_ key, open the _Quick Light_ MCM and you should see the option. The same is true for _CGO_, there are options for _Grip Shift_ and _Dual Wield Blocking_.

## Game MCM Options

**NOTE:** Any menus or options not specifically mentioned here can be ignored.

It is _very important_ to **wait** until _all_ messages have both ceased appearing and disappearing in the upper left corner of the screen before continuing.

## A Matter of Time

Load the User Preset.

##  CGO

Note that the "Grip Shift" key is set to **V** and "Dual Wield Block" is set to **MOUSE 3** (the mouse wheel button). These can be changed as needed.

### Settings

#### Leaning

**I recommend the following values:**

_Lean Multiplier (1st Person)_: _X0.00_

_Lean Multiplier (3rd Person)_: _X0.25_

_Camera Noise_

_Camera Noise Mult (1st Person)_: _X0.00_

Scroll all the way down.

## FG Animation Selector

Note that the key to bring up a menu of "Flower Girls" animations is SHIFT. This can be changed as needed.

## Flower Girls SE

A lot of this is up to personal preference. 

### Main Options

If you want sexual favors to be free and easy, uncheck "Service Charge" and "Enable Seduction".

Strapons are up to you but they will probably clip badly. Be sure to choose the CBBE option.

### Hotkeys

If you want to change the FreeCam Key, you will have to save and reload so Flower Girls can detect PapyrusUtil.

##  Follower Framework

###  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

## LOTD: The Curator's Companion

Some users have reported excessive lag with occasional inventory scans of the Dragonborn Museum when reaching near-capacity (over 1,000 displays and over 100 hours of gameplay)

If this sounds like you, navigate to the _MoreHUD & Scan_ portion of this MCM and set "Museum Scan Interval (Minutes)" to _120_.

## OBIS Bandits

This mod needs to be enabled so under

### Settings

Put a check in the "Enable" box.

I also highly recommend you change "Extra Bandits" to **1** or every time this mod calls for additional spawns all bandits in the area will be **multiplied by five.**

## ostim

Begin by scrolling all the way to the bottom right and choosing "Import Settings." WAIT THREE SECONDS, then click okay. If you are eager to play, nothing else is required. Sex scenes will activate and play automatically with no input needed from you.

Scroll back to the top and set this fantastic mod up how you see fit.

I recommend you carefully read the mod pages for both "OSex" and "OStim" if you wish to configure sex into an interactive little "minigame". I do NOT recommend you alter the values for stripping, clippingless first person (it's actually bugged and causes flicker), flipped animation fix, or use beds (also sometimes bugged). Spend time examining how the controls work. It's a little tough to get used to but the gist is that you use 8,4,5, and 6 on the NUMPAD like another set of WASD keys to move around in the OSex menus. 7 chooses a command, 1 cancels a command. + is inspect, enter is open or close menu. Period or decimal ends the scene. 

Remember that at any time you can go up to anyone and press the up arrow to have OSex sex with them.

## Quick Light

This is automatically set to NUMPAD 1. Feel free to change it.

## SKY UI

### General

Set _Font Size_ to Small.

Disable the _Active Effects HUD_. (It gets in the way of my AMOT preset.)

## SmoothCam

### Presets

Click on _Slot 2: EasyEase_ under _Load Preset_ on the **RIGHT SIDE OF THE SCREEN** and wait for the message.

## Trade and Barter

Click "Modify Barter Settings" and change the "Preset" to your liking, but I recommend "Medium."

## All done!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. There are two options to start your game. The first is to talk to the Mara statue for a more traditional method. Sexy starts (most of the time involving you being naked) are available from the bookshelf nearby.

# ULTRA MEGA IMPORTANT

**The Ultimate Dodge** will **NOT** work until you leave the starting cell after sleeping on the bed after talking to the statue or choosing a book. It will also **NOT** work **UNTIL YOU PRESS G TWICE.** The **FIRST** thing you should do as soon as you spawn is **PRESS G TWICE**. If you message me about how you are stuck in the air after a dodge, I will tell you to read this entire readme again.
