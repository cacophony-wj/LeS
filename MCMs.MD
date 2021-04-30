- [Licentia Configuration](#licentia-configuration)
  - [Setting your resolution](#setting-your-resolution)
  - [Character Creation](#character-creation)
  - [AS SOON AS CHARACTER CREATION IS COMPLETE](#as-soon-as-character-creation-is-complete)
  - [A bit of a note on System Settings](#a-bit-of-a-note-on-system-settings)
  - [Controls](#controls)
  - [DEFAULT CONTROLS AND HOW TO CHANGE THEM](#default-controls-and-how-to-change-them)
  - [Game MCM Options](#game-mcm-options)
  - [A Matter of Time](#a-matter-of-time)
  - [CGO](#cgo)
    - [Settings](#settings)
      - [Leaning](#leaning)
  - [Follower Framework](#follower-framework)
  - [Fertility_Mode](#fertility_mode)
    - [System](#system)
  - [LOTD: The Curator's Companion](#lotd-the-curators-companion)
  - [OBIS - Bandits](#obis---bandits)
  - [OStim](#ostim)
    - [Configuration](#configuration)
      - [Sex Scenes](#sex-scenes)
      - [Beds](#beds)
      - [Undressing](#undressing)
    - [How To Use This Mod](#how-to-use-this-mod)
  - [Quick Light](#quick-light)
    - [SexLab Solutions](#sexlab-solutions)
      - [follower](#follower)
  - [SKY UI](#sky-ui)
    - [General](#general)
  - [SmoothCam](#smoothcam)
    - [Presets](#presets)
  - [Trade and Barter](#trade-and-barter)
  - [VioLens](#violens)
    - [Profile System](#profile-system)
  - [All done!](#all-done)
- [ULTRA MEGA IMPORTANT](#ultra-mega-important)

# Licentia Configuration

## Setting your resolution

_Licentia AGT_ has been configured to run at _2560x1440_ by default. If you wish to change this to a higher or lower resolution, click the hammer and gear icon and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. (Should be under [Display] which is itself in alphabetical order.) Change the values for _iSize H_ and _iSize W_ to the resolution you wish. Below are some common resolutions you can use.

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/1778). Install it as you would any other Mod Organizer mod. Just put it under _Added Mods._

I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard). I have also recently included a host of presets from one of my users, featuring male and female variants for every race, including Argonians and Khajiit.

Tweak to your liking, but bear in mind that many of the close-cropped hairstyles will **NOT** look right until you select the _High Poly Head_ by navigating to the _Head_ portion of RaceMenu and choose _Face Part 3_ (near the bottom). You might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Experiment and figure it out. One thing you can do is open the console with the _Tilde `_ key, click on yourself, and type _unequipall_, and then reload your preset to go nude. Click _Done_ (in the lower left) when you are finished.

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

**DO NOTHING** until **ALL** of the messages in the top left corner stop appearing. This is the most script intensive part of the game and may break otherwise. (It almost certainly will break if you forgot to copy game folder files.)

## A bit of a note on System Settings

## Controls

**Under the System > Settings Menu** change _Quicksave_ to _F9_, and _Quickload_ to _F10_. Don't worry about using them because _Engine Fixes_ converts them to full saves. 

## DEFAULT CONTROLS AND HOW TO CHANGE THEM

The vast majority of these options are configured in the "Controls" portion of Skyrim's pause menu. Please take note that your "Sneak" key is **NO LONGER SNEAK**, it is **DODGE** instead. If you wish to select a sneak key, first configure your **DODGE** key (which is labeled as **SNEAK** in the "Controls" menu, remember, and is assigned to **CTRL** by default). Then open the MCM and choose the _Ultimate Dodge_ option. There is an entry there for "Sneak Key", click it and choose. In the end I think you will be better served with Dodge as _Shift_ and Sneak as _CTRL_.

To change the _Quick Light_ key, open the _Quick Light_ MCM and you should see the option. The same is true for _CGO_, there are options for _Grip Shift_ and _Dual Wield Blocking_.

## Game MCM Options

**NOTE:** Any menus or options not specifically mentioned here can be ignored. I have used what limited xEdit and Papyrus knowledge I possess to configure them automatically at game init (while those messages were cycling earlier)

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

## Fertility_Mode

First "Enable" the mod. This is a _slow_ process. Give it about 30 seconds to check itself.

Check _Unique Women Only_ and _Unique Men Only_.

The only other options you may be interested in are under "Automation" in the lower right.

The _Spouse Fidelity_ option is hilarious if you set it down to around 50%. This basically means you have more baby mama drama than an Oklahoma trailer park.

_Randomly Inseminate_ allows you to simulate widespread fucking without acting it out. Be wary of this mode!

Finally, under _Information_, the _Show Verbose Messages_ option with pop up various methods on Skyrim's sexual exploits such as, with spouse fidelity low: "Embry came inside Gerdur."

###  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

## LOTD: The Curator's Companion

Some users have reported excessive lag with occasional inventory scans of the Dragonborn Museum when reaching near-capacity (over 1,000 displays and over 100 hours of gameplay)

If this sounds like you, navigate to the _MoreHUD & Scan_ portion of this MCM and set "Museum Scan Interval (Minutes)" to _120_.

## OBIS - Bandits

First Enable the mod, then decide how many extra bandits you want at every bandit spawn. I find the default of 3 to be overwhelming early on and set it to 1.

## OStim

The settings in this extensive mod are almost all down to personal preference. I recommend you carefully read the mod pages for both "OSex" and "OStim" if you wish to configure sex into an interactive little "minigame". 

However, I do have the following recommendations:

### Configuration

#### Sex Scenes

Uncheck "Actors Control Speed."

Set the "Excitement Multiplier" to 3.00.

#### Beds

Uncheck "Use Beds". Nice idea but too buggy.

#### Undressing

Uncheck everything but "Fully undress at start."

### How To Use This Mod

OSex is a little tough to get used to but the gist is that you use 8,4,5, and 6 on the NUMPAD like another set of WASD keys to move around in the OSex menus. 7 chooses a command, 9 swaps actors or functions, 1 cancels a command. + is inspect / advance scene, enter is open or close menu. Period or decimal ends the scene. 

If you are unfortunate and have a 75% keyboard or some other device without a NUMPAD, you will have to use an autohotkey script or remap the OSex controls somehow. Join my private server and search the #licentia channel for tips. You can find the link in the #sse-licentia channel on the Wabbajack Discord.

Bear in mind that many subjects do not have appropriate animations (such as lesbian scenes). To find these, press the backslash key \ at any time, type in a keyword, and press Enter to begin.

At any time you can go up to anyone and press the up arrow to have OSex sex with them.

Creatures do not function with OSex and I have no plans to ever implement them. Play DND.

## Quick Light

This is automatically set to NUMPAD 1. Set it to whatever you wish. All it does is turn on a light so you can see around you.

###  SexLab Solutions

####  follower

Choose the appropriate options here to offer a follower instead of yourself for sexual favors. This is mainly useful if you aren't attracted to a particular sex.

## SKY UI

### General

Set _Font Size_ to Small.

Disable the _Active Effects HUD_. (It gets in the way of my AMOT preset.)

## SmoothCam

### Presets

Click on _Slot 2: EasyEase_ under _Load Preset_ on the **RIGHT SIDE OF THE SCREEN** and wait for the message.

## Trade and Barter

Click "Modify Barter Settings" and change the "Preset" to your liking, but I recommend "Medium."

## VioLens

### Profile System

Click _Load_ and select _VioLens._ Wait about three seconds until the menus stop cycling.

## All done!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. I have expanded roleplaying options from the beginning of the game with the mod "Abandoned Prison Tweaks." First turn around and grab the key and mirror on the shelf nearby. The mirror is what you should use to change your appearance -- it causes far fewer bugs than the ``showracemenu`` command. The book provides a little flavor text on how you got where you are. The key opens the cabinet nearby, which you should do now. Inside you will find a chest with scrolls to assign your starting spells -- take all of them if you are a power gamer, or only the ones that represent your background. All starting spells have been removed. On the middle shelf is another key, which you should grab, and a cask with a few potions in it. On the bottom shelf is a chest with various crappy starting gear you can choose. Return your attention to the top shelf again. Somewhere floating around all glitchy is the "Firmament" book which, when read, will allow you to choose any Standing Stone buff in the game. (I really need to fix the placement of this.) There are two ways to choose where you will spawn. The statue, as in most lists, provides a host of specfic roleplaying options. The books on the upper left of the cabinet will allow you to choose a sexy start where you are stripped of all your clothes -- great for roleplaying with your chosen gear. After choosing one, check the small chest hidden behind a barrel in the corner where you started for a dozen lockpicks if you wish to take them. Then sleep on the bed to begin. **THE VANILLA START WORKS FINE IF YOU LIKE IT OLDSCHOOL.** Just make sure you spend a few seconds waiting for any final initialization scripts to execute before you sleep in the bed, and you can be the Dragonborn Prisoner you always have been.

# ULTRA MEGA IMPORTANT

**The Ultimate Dodge** will **NOT** work until you leave the starting cell after sleeping on the bed after talking to the statue or choosing a book. It will also **NOT** work **UNTIL YOU PRESS G TWICE.** The **FIRST** thing you should do as soon as you spawn is **PRESS G TWICE**. If you message me about how you are stuck in the air after a dodge, I will tell you to read this entire readme again.
