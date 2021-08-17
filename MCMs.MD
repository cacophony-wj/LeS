- [Licentia Configuration](#licentia-configuration)
  - [Setting your resolution](#setting-your-resolution)
  - [Customizing Controls](#customizing-controls)
  - [Using A Controller](#using-a-controller)
  - [Character Creation](#character-creation)
  - [AS SOON AS CHARACTER CREATION IS COMPLETE](#as-soon-as-character-creation-is-complete)
  - [Game MCM Options](#game-mcm-options)
  - [A Matter of Time](#a-matter-of-time)
  - [CGO](#cgo)
    - [Settings](#settings)
      - [Leaning](#leaning)
  - [Completionist](#completionist)
  - [Fertility Mode+](#fertility-mode)
  - [OStim](#ostim)
    - [Configuration](#configuration)
      - [Sex Scenes](#sex-scenes)
      - [Beds](#beds)
      - [Undressing](#undressing)
    - [How To Use This Mod](#how-to-use-this-mod)
    - [OStrap](#ostrap)
  - [Quick Light](#quick-light)
    - [SexLab Solutions](#sexlab-solutions)
      - [follower](#follower)
  - [SKY UI](#sky-ui)
    - [General](#general)
    - [Advanced](#advanced)
  - [SmoothCam](#smoothcam)
    - [Presets](#presets)
  - [Trade and Barter](#trade-and-barter)
  - [VioLens](#violens)
    - [Profile System](#profile-system)
  - [Now you are ready to spawn!](#now-you-are-ready-to-spawn)
  - [ONE FINAL STEP](#one-final-step)
  - [Genesis Surface Spawns, Genesis Spawns Unleashed](#genesis-surface-spawns-genesis-spawns-unleashed)
- [ULTRA MEGA IMPORTANT](#ultra-mega-important)
  
# Licentia Configuration

## Setting your resolution

_Licentia_ has been configured to run at _1920x1080_ by default. If you wish to change this to a higher or lower resolution, click the puzzle piece icon and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. 

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need to enable all of the mods in the "UltraWide" section of the modlist. I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Customizing Controls

The vast majority of these options are configured in the "Controls" portion of Skyrim's pause menu. Please take note that your "Sneak" key is **NO LONGER SNEAK**, it is **DODGE** instead. If you wish to select a sneak key, first configure your **DODGE** key (which is labeled as **SNEAK** in the "Controls" menu, remember). Then open the MCM and choose the _Ultimate Dodge_ option. There is an entry there for "Sneak Key", click it and choose. In the end I think you will be better served with Dodge as _Shift_ and Sneak as _CTRL_.

To change the _Quick Light_ key, open the _Quick Light_ MCM and you should see the option. The same is true for _CGO_, there are options for _Grip Shift_ and _Dual Wield Blocking_.

The last control you need to configure is within the _True Directional Movement_ mod. I recommend setting the "Lock-On" key to one of your alternate mouse buttons, such as the scroll wheel or one of the side buttons, if you have one.

## Using A Controller

Due to a request from multiple users I have enabled all controller mods by default. They can be found under "Controller Options", but serve no purpose so long as you use a mouse and keyboard. However, if you wish to play with a controller, you will have to **delete any ControlMap_Custom" file(s) in your Skyrim game directory.** You will have to configure CGO (I recommend D-Pad Left for grip shift and LB for Dual-Wield Blocking), The Ultimate Dodge Mod (I recommend D-Pad Down for Sneak), and Quick Light (I recommend D-Pad Up). There is no good button for lock-on, I typically assign the same one as Spring and Dual-Wield Blocking (LB).  Finally, reconfigure your QuickSave and QuickLoad keys in-game. You must ALSO recall that almost ALL OStim navigation can only be accomplished via the keyboard, so you will have to either switch back and forth or set to autopilot. When all is said and done the Gamepad controls will be as follows:

- Start: Journal
- Back: Wait
- LT: Left Attack
- RT: Right attack
- LB+Back: Quicksave
- RB+Start: Tween menu (character menu)
- LB+RB: Shout (in that order, you kinda haveta roll your fingers across them)
- LB: Lock-on (toggle)
- RB: Sprint, Dual-Wield Block
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

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard). I have also recently included a host of presets from one of my users, featuring male and female variants for every race, including Argonians and Khajiit.

Tweak to your liking, but bear in mind that many of the close-cropped hairstyles will **NOT** look right until you select the _High Poly Head_ by navigating to the _Head_ portion of RaceMenu and choose _Face Part 3_ (near the bottom). You might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Most of the options will not function correctly until you have completed character creation at least once -- when you have done so, turn around and use the "Vanity Mirror" to make final adjustments. (Don't go too crazy with the dong, or it will poke through people.) This option is basically the same thing as Riften's "Face Sculptor" and causes none of the bugs and dropped racial and magic effects that the _showracemenu_ command does. Experiment and figure it out. 

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

**DO NOTHING** until **ALL** of the messages in the top left corner stop appearing. This is the most script intensive part of the game and may break otherwise. (It almost certainly will break if you forgot to copy game folder files.)

## Game MCM Options

**NOTE:** Any menus or options not specifically mentioned here can be ignored. I have used what limited xEdit and Papyrus knowledge I possess to configure them automatically at game init (while those messages were cycling earlier)

## A Matter of Time

Load the User Preset.

##  CGO

### Settings

#### Leaning

**I recommend the following values:**

_Lean Multiplier (1st Person)_: _X0.00_

_Lean Multiplier (3rd Person)_: _X0.00_

_Camera Noise_

_Camera Noise Mult (1st Person)_: _X0.00_

## Completionist

This mod is intended as a fantastic companion to your own Quest Journal, informing you of ALL the quests available in a particular area as well as from added mods in this list - so you will never be without something to do! Refer here if you are at a loss and do whatever you feel is of interest. Two things to keep in mind, if you click on a quest it will "Manually" complete it and you will have to reset them all to get it back, so don't do that unless the MCM bugs out and the quest does not complete on its own! Second, _this mod does not update with quest steps._ It will not tell you where to go and what to do, your normal Journal serves that purpose -- only what is necessary to start a quest, as well as a notification that it has completed.

## Fertility Mode+

_Be Warned:_ This mod is _very_ intrusive, with a lot of "heavy" features. If this concerns you, or you do not wish to deal with the difficulty inherent from possessing a full fertility and reproductive cycle, **do not** enable this mod, as in its current state it **can not** be fully disabled again. If this is not a concern of yours...

"Enable" the mod. This is a _slow_ process. It will lock up the MCM menu, most likely, so you will have to exit all menus and re-enter.

Check _Unique Women Only_ and _Unique Men Only_.

The only other options you may be interested in are under "Automation" in the lower right.

The _Spouse Fidelity_ option is hilarious if you set it down to around 50%. This basically means you have more baby mama drama than an Oklahoma trailer park.

_Randomly Inseminate_ allows you to simulate widespread fucking without acting it out. Be wary of this mode!

Finally, under _Information_, the _Show Verbose Messages_ option with pop up various methods on Skyrim's sexual exploits such as, with spouse fidelity low: "Embry came inside Gerdur."

## Follower Framework

Back due to popular demand and a policy change by Nether.

### System

Click _Load Profile_

There are a LOT of things you can do with this, like make your followers into tanks, change their outfits, give them homes they live in, even the dogs and cats, too, which is the main reason I want this in the first place. Dig around in there and figure it out. 

## OStim

The settings in this extensive mod are almost all down to personal preference. I recommend you simply "Import Settings" to get my recommendations (scroll all the way down, on the right).

### How To Use This Mod

OSex is a little tough to get used to but the gist is that you use 8,4,5, and 6 on the NUMPAD like another set of WASD keys to move around in the OSex menus. 7 chooses a command, 9 swaps actors or functions, 1 cancels a command. + is inspect / advance scene, enter is open or close menu. Period or decimal ends the scene. 

If you encounter a scene that is terribly out of alignment, press the L key to open a menu with tons of options for adjustments. If you save your changes they will persist for that animation.

Bear in mind that many subjects do not have appropriate animations (such as lesbian scenes). To find these, press the backslash key \ at any time, type in a keyword, and press Enter to begin.

At any time you can go up to anyone and press the up arrow to have OSex sex with them.

Creatures do not function with OSex and I have no plans to ever implement them.

### OStrap

I am not a fan of strap-ons, but I am even less of a fan of futa options. Not that there is anything wrong with either, but I have experienced _extreme_ reactions from futa options appearing in-game unexpectedly. If you wish to include futa options in your game, you can find a pinned message in great detail on my private server. I recommend the following options for _OStrap_:

_OStrap Core_

"Enable mod" and "Enable for NPC." Use "Enable for Player" only if you are female.

_OStrap Integrations_

"Enable OCum Support"

_Enabled Strapons_

All.

## Quick Light

This is automatically set to NUMPAD 1. Set it to whatever you wish. All it does is turn on a light so you can see around you.

###  SexLab Solutions

####  follower

Choose the appropriate options here to offer a follower instead of yourself for sexual favors. This is mainly useful if you aren't attracted to a particular sex.

## SKY UI

### General

Set _Font Size_ and _Icon Size_ to your preference, likewise with _Category Icon Theme_. (I personally only really like the "Celtic" version of the icons.)

### Advanced

Due to the location of additional HUD elements like the minimap, under "Active Effects HUD" you will need to set _Vertical Anchor_ to "Center".

## SmoothCam

### Presets

Click on _Slot 4: Modern_ under _Load Preset_ on the **RIGHT SIDE OF THE SCREEN** and wait for the message.

## Trade and Barter

Click "Modify Barter Settings" and change the "Preset" to your liking.

## True Directional Movement

I recommend you leave most of these options alone, but lock-on is off by default, and it's the best lock-on I've ever seen. Enable the hotkey to your preference under

### Target Lock

But I recommend MOUSE 3 or 4 for MKB and "LB/L1" for Controller.

## VioLens

### Profile System

Click _Load_ and select _VioLens._ Wait about three seconds until the menus stop cycling.

## Now you are ready to spawn!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. I have expanded roleplaying options from the beginning of the game with the mod "Abandoned Prison Tweaks." First turn around and grab the key and mirror on the shelf nearby. The mirror is what you should use to change your appearance -- it causes far fewer bugs than the ``showracemenu`` command. The book provides a little flavor text on how you got where you are. The key opens the cabinet nearby, which you should do now. Inside you will find a chest with scrolls to assign your starting spells -- take all of them if you are a power gamer, or only the ones that represent your background. All starting spells have been removed. On the middle shelf is another key, which you should grab, and a cask with a few potions in it. On the bottom shelf is a chest with various crappy starting gear you can choose. Return your attention to the top shelf again. Somewhere floating around all glitchy is the "Firmament" book which, when read, will allow you to choose any Standing Stone buff in the game. (I really need to fix the placement of this.) There are two ways to choose where you will spawn. The statue, as in most lists, provides a host of specfic roleplaying options. The books on the upper left of the cabinet will allow you to choose a sexy start where you are stripped of all your clothes -- great for roleplaying with your chosen gear. After choosing one, check the small chest hidden behind a barrel in the corner where you started for a dozen lockpicks if you wish to take them. Then sleep on the bed to begin. Unfortunately, INI tweaks necessary for clippingless first person mode to function properly render the vanilla start unplayable. I recommend you choose "camping in the woods" if you want to begin near Helgen. It is highly unlikely that I will disable the tweaks necessary for clippingless first person.

## ONE FINAL STEP

Once you reach your chosen location and have dispensed with any tutorials and or cutscenes, there are a couple further steps. Return to the MCM menus listed below.

## Genesis Surface Spawns, Genesis Spawns Unleashed

The meat of _Licentia's_ difficulty. Spawns extra enemies in each area. I tested with everything maxed, incuding OBIS, and it was _tough_ at early level. Probably something like 4 additional spawns for each mod is more appropriate.

# ULTRA MEGA IMPORTANT

**The Ultimate Dodge** will **NOT** work until you leave the starting cell after sleeping on the bed after talking to the statue or choosing a book. It will also **NOT** work **UNTIL YOU PRESS G TWICE.** The **FIRST** thing you should do as soon as you spawn is **PRESS G TWICE**. If you message me about how you are stuck in the air after a dodge, I will tell you to read this entire readme again.
