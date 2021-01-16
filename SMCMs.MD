- [Servitium Configuration](#servitium-configuration)
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
    - [Changes for Servitium](#changes-for-servitium)
    - [Animation Settings](#animation-settings-1)
  - [SexLab](#sexlab-2)
  - [SAVE AND LOAD!](#save-and-load)
  - [ZaZ Animation Pack](#zaz-animation-pack)
    - [General](#general)
  - [SL Anim Loader](#sl-anim-loader)
    - [General Options](#general-options)
  - [A Matter of Time](#a-matter-of-time)
  - [AGO](#ago)
    - [Settings](#settings)
  - [Ashes](#ashes)
  - [BBLS](#bbls)
    - [Basic Settings](#basic-settings)
    - [Resource Heavy](#resource-heavy)
  - [CBBE 3BBB Addon](#cbbe-3bbb-addon)
  - [CGO](#cgo)
    - [Settings](#settings-1)
      - [Unlocked Grip](#unlocked-grip)
      - [Dodge Roll](#dodge-roll)
      - [Dual Wield Blocking](#dual-wield-blocking)
      - [Unlocked Movement](#unlocked-movement)
  - [Clockwork](#clockwork)
  - [Deadly Dragons](#deadly-dragons)
    - [Dragons](#dragons)
      - [Special](#special)
  - [Diverse Dragons Col. 3](#diverse-dragons-col-3)
    - [Dragons](#dragons-1)
  - [Extended UI](#extended-ui)
  - [FEC](#fec)
    - [Player Effects](#player-effects)
    - [Fire](#fire)
      - [Fire Effects](#fire-effects)
      - [Immersion](#immersion)
    - [Frost](#frost)
      - [Frost Effects](#frost-effects)
    - [Shock](#shock)
      - [Shock Effects](#shock-effects)
      - [Immersion](#immersion-1)
    - [Poison](#poison)
  - [Follower Framework](#follower-framework)
    - [System](#system)
  - [GIST Soul Trap](#gist-soul-trap)
    - [Leveling](#leveling)
  - [Growl Werebeasts](#growl-werebeasts)
  - [Quick Light](#quick-light)
  - [Sacrosanct Vampires](#sacrosanct-vampires)
  - [Serio's Hotkeys](#serios-hotkeys)
  - [SexLab Adventures](#sexlab-adventures)
  - [SexLab Aroused](#sexlab-aroused)
      - [Settings](#settings-2)
  - [SexLab Eager NPCs](#sexlab-eager-npcs)
    - [General](#general-1)
    - [SexLab Solutions](#sexlab-solutions)
      - [follower](#follower)
  - [SexLab Tools](#sexlab-tools)
    - [Settings](#settings-3)
  - [SL Survival](#sl-survival)
  - [SKY UI](#sky-ui)
    - [General](#general-2)
    - [Advanced](#advanced)
  - [SmoothCam](#smoothcam)
    - [Compatibility](#compatibility)
    - [Presets](#presets)
  - [Spank That Ass](#spank-that-ass)
  - [SPERG](#sperg)
    - [Fixes & Compatibility](#fixes--compatibility)
    - [Advanced](#advanced-1)
  - [SSoB](#ssob)
  - [Storm Lightning](#storm-lightning)
    - [presets](#presets-1)
  - [Wildcat Combat](#wildcat-combat)
  - [The Ultimate Dodge Mod](#the-ultimate-dodge-mod)
    - [NPC Settings](#npc-settings)
  - [All done!](#all-done)

# Servitium Configuration

## Setting your resolution

_Licentia_ has been configured to run at _1920x1080_ by default. This not only ensures higher FPS, but also quick turnaround for the various "animations" which are laggy in the best of situations. If you wish to change this to a higher resolution, click the hammer and gear icon and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. (Should be under [Display] which is itself in alphabetical order.) Change the values for _iSize H_ and _iSize W_ to the resolution you wish. Below are some common resolutions you can use.

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/1778). Install it as you would any other Mod Organizer mod. Just put it under _Added Mods._

I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Character Creation

**If you look really old** no matter what you try, reset your Complexion in the _Head_ menu. Vanilla Nord Female Preset 01 is an old hag for some weirdass reason and RaceMenu doesn't reset it properly. 

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard).  There are no presets for Argonians and Khajiits for some reason. I made two male presets, a mage and a warrior, with an (M) after the name. Keep in mind that if you choose a _male elf_ character, the facial hair will look weird unless you switch the _Face Part_ to **3.** You'll know you have the right one when it says "high poly" in the bottom right and the face suddenly looks far more detailed. Tweak to your liking, you might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Experiment and figure it out. One thing you can do is open the console with the _Tilde `_ key, click on yourself, and type _unequipall_, and then reload your preset to go nude. Click _Done_ (in the lower left) when you are finished.

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

You will get a **POPUP** from "The Curators Companion". Answer Ok and **DO NOTHING** until you get another popup. Click _Scan Later_. After a third popup, you should be ready to continue.

## A bit of a note on System Settings

## Controls

The controls for "Licentia" have been set to controller by default. I'm old and don't handle buttons well. If you wish to use a controller like me, please be certain to **delete** any _ControlMap_Custom_ files in your Skryim **game* directory if you plan to do so. Note that you will have to bind any keyboard controls again (such as QuickSave / QuickLoad)

Unfortunately 8-way dodges are not possible with a controller without an external program and forcing "always run" which is esssential to any type of Sneak. As you play, keep in mind that you can roll or step dodge in only the four cardinal directions. 

**Under the System > Settings Menu** change Quicksave_ to _F9_, and _Quickload_ to _F10_. Don't worry about using them because _Engine Fixes_ converts them to full saves. 

_I've been through the turnstile and am coming at you inverted._ **So are my controls.** If you don't like an inverted up and down you may have to change it yourself.

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

I have removed all Futa options because I am not into them. Remaining are seven strapons of varying ridiculousness. If you don't want them click on each one until none are left.

If you do want your females to sometimes use strapons, navigate to

### Animation Settings

and click the mark on the right that reads _Females Use Strap-ons._

There is an option here that significantly affects many of the _Amorous Adventures_ scenes. Sometimes, the quests want a particular foreplay animation to play, but I have disabled _Foreplay_ to minimize the time spent watching a scene. If you want the AA animations to make more sense at the cost of an additional scene at the beginning of every adult interaction, go ahead and enable this option.

Note that **ALL** of _SexLab's_ original old animations have been suppressed due to unpopularity. If you want to re-enable them for some reason, click _CLEAR SUPPRESSED LIST - CLICK HERE_

### Changes for Servitium

You **WILL** need to enable _Separate Orgasms_ here on the left or you will never be able to orgasm. Talk about Hell!

### Animation Settings

**Creature animations are not included.** For additions such as these, join my private Discord server which is linked in the main channel of this modlist.

## SexLab

## SAVE AND LOAD!

Lover's Lab recommends saving and loading the game immediately after fully configuring SexLab. Please do so now. If the QuickSave and QuickLoad buttons have changed, recall that they are now _F9_ and _F10_.

## ZaZ Animation Pack

### General

Change all of the _Update Interval_ values to their maximums.

None of the other options really do anything without a Devious setup. This mod is mainly here so Defeat will activate, and I forgot to enable Defeat. It's probably for the best.

##  SL Anim Loader

### General Options

Click _Enable All: Click Here_

Click _Register Animations_

The process will take about two minutes, whereupon you will receive a message that animations have been registered. Just click _Accept_

## A Matter of Time

Load the User Preset.

## AGO

### Settings

Under _Enable/Disable_ deselect _Persistent Arrows_

**If you use Defeat** you will want to disable all arrow bleeding as well.

## Ashes

I recommend setting this to strip all your belongings to simulate _Defeat_ without actually using _Defeat_, but the bare minimum should be to enable the mod since it prevents save corruption. The best way to use it is to wait until you spawn at Riverwood and reload.

## BBLS

### Basic Settings

You can do whatever you want here, but these options are a _lot_ of fun. 

### Resource Heavy

These do appear to be quite heavily scripted. I recommend leaving them as is, but feel free to experiment. _Business Options,_ where you act as manager of the _Luxury Suite_, could be really fun for all I know.

You will probably have to exit the menu and re-enter it to continue.

## CBBE 3BBB Addon

I recommend setting all of the _Use Slots_ to **60 - Devious Devices Compatible**. This is not because Devious is installed, but because the various bikinis and other slooty outfuts use all those same slots.

##  CGO

### Settings

#### Unlocked Grip

This switches the way you hold a weapon. You can use anything one or two handed, but can only block with a shield in one-handed mode. Set the key for switching grip here. For controller, I recommend D-Pad Left. For keyboard, I recommend B.

Uncheck "NPCs Change Grip" if it is checked.

#### Dodge Roll

We need to disable this. Set it to _Hotkey (Tap)_ and leave the key as _ESC_ (which basically means blank)

_Leaning_

**I recommend the following values:**

_Lean Multiplier (1st Person)_: _X0.00_

_Lean Multiplier (3rd Person)_: _X1.00_

_Camera Noise_

_Camera Noise Mult (1st Person)_: _X0.00_

Scroll all the way down.

#### Dual Wield Blocking

This also affects unarmed blocks. Set it to the button you prefer, I recommend either mouse 3 (scroll wheel) or RB / R1.

#### Unlocked Movement

Make certain all of these are unchecked.

## Clockwork

If you hate frustration, set _Gilded Recovery Time_ to "6 Hours." If you love it, leave it at 3.

## Deadly Dragons

### Dragons

#### Special

Uncheck "Knockdown"

I like my life to suffer a bit more on _Servitium_. I recommend setting the difficulty to _Expert._ Dragons will MACK you if you're not careful.

## Diverse Dragons Col. 3

### Dragons

Disable _Nether_, _Sanguine_, and _Vile_. These dragons are almost impossible to beat, and also hideously ugly. As in, badly designed.

## Extended UI

Check the boxes marked _Show attribute modifiers_ and _Show skill modifiers

## FEC

### Player Effects

Check "Soul Absorb"

### Fire

#### Fire Effects

Uncheck "Automatic" 

Check "Skeletonize"

#### Immersion

Uncheck "Fire Damage"

### Frost

#### Frost Effects

Uncheck "Automatic" 

Check "Shatter"

### Shock

#### Shock Effects

Uncheck "Automatic"

Check "Explosive" 

#### Immersion

Uncheck "Shock Damage"

### Poison

Set _Poison color intensity_ to 0%. This is really the only option you _MUST_ enable, otherwise you'll get weird things with dicks when people die due to poison.

##  Follower Framework

###  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

## GIST Soul Trap

Check "Show message on soul trapped"

Some people like to link soul gem expertise to Enchanting, if you do too go to 

### Leveling

Check _Enable Leveling System_ and then choose _Enchanting_.

## Growl Werebeasts

Check "Invulnerable during Transformation"

## Quick Light

Set Type to "No Special Effect"

Brightness to "Normal"

"Set light key"... I recommend D-Pad Up for controller and NUMPAD1 for keyboard.

## Sacrosanct Vampires

Click _Fortitude: Disable_

## Serio's Hotkeys

Recommend _Use Vanilla Hotkeys_ if you're on controller.

You'll have to read about the mod if you wanna use it, I'm still experimenting. Basically you can set it so your hotkeys are a function of shoulder button + face button for a total of 8 hotkeys on the controller (kinda like FF14 if you've ever played that on console)

## SexLab Adventures

Choose _Load From File_ and "NoPovertyOrCrime.json". Wait about 10 seconds, the menu will flicker. Then click "Install" and wait for everything to update. You'll know it when it happens.

##  SexLab Aroused

#### Settings

_General_

On the right, import the profile.

##  SexLab Eager NPCs

###  General

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


## SL Survival

This mod is extremely bloated. In setting it up, I got frustrated so many times I almost considered removing it despite all the crazy features it adds. It shares this in common with _Cursed Loot_, another mod that's too bloated in my opinion. Unlike Cursed Loot, however, it seems this mod (aside from the _MCM_) works properly once you understand how you're supposed to use it.

I'll save the gameplay talk for the channel. For now, you are going to have to _Import Profile_ on the main page. _Wait until all the messages cycle_ and hang up at "Actioning Settings." It's not supposed to hang here but it does. Exit all menus.

Now this part is very picky. Sit and **do nothing** in the starting cell until you receive two messages: "Building Bikini List", and a minute or two later "Building Bikini List Complete." 

Now you're going to have to give it a little kick for it to finish. Open the _MCM_ again and return to the _SL Survival Menu_. Once you see the main page of settings, exit the MCM again, and wait for two messages: "Building Pickpocket List" and a few minutes later "Pickpocket List Complete."

There. _SL Survival_ is now configured and all executing scripts are complete.

There are a few caveats. Licenses are on by default, which means you cannot carry or sell weapons or armor without buying one. They are available usually from a given keep's dungeon, but in Whiterun it is a small building behind the alchemist. If you want to disable this, go to _Licenses 1_ in the MCM and turn it off. The only reason it is this way is because it must be enabled to import a setting that allows bikini experience to work. One made, this change remains even if licenses are disabled. I strongly recommend you disable it because it is highly annoying.

Another annoying option is Tolls. This prevents you from leaving cities without a follower and payment of a fee (click on the strongbox on a nearby table to pay it). I find this option highly annoying and disable it. You can do so under "Tolls, Evictions and Gates."

Finally, under the main "Settings" category there is an option at the bottom called "Enable Map & Compass Mechanics." I HATE HATE HATE HATE HATE this feature. It keeps you from having a compass or map until you buy one and they're stupid expensive. Not only that they often don't show up at the merchant for a few days. I recommend disabling it, but _you will have to do so every time you start Skyrim._ Yes, it fucking sucks.

This will also help you on your _Dungeons & Deviousness_ installation if you still have one.

## SKY UI

### General

Set _Font Size_ to Small.

Disable the _Active Effects HUD_. (It gets in the way of my AMOT preset.)

### Advanced

Disable the map menu one because of SL Survival's bullshit.

## SmoothCam

### Compatibility

Alternate Conversation Camera: Checked

Improved Camera: Checked

Immersive First Person View: Unchecked

Scroll to the bottom where you will find 

### Presets

Click on _Slot 2: EasyEase_ under _Load Preset_ on the **RIGHT SIDE OF THE SCREEN** and wait for the message.

## Spank That Ass

Click _Import Settings._

## SPERG

### Fixes & Compatibility

Unarmed Mode: Manual

### Advanced 

Advanced Options: Enable

Weapon Speed: Disabled

## SSoB

Check "Quest Markers on Stones of Berenziah"

## Storm Lightning

### presets

Click _Realistic_ and wait for it to say **DONE**

## Wildcat Combat

Check "Disable Dynamic Combat."

Under **difficutly** check "Allow Wildcat to Manage Difficulty"

## The Ultimate Dodge Mod

Highly recommend you set the sneak key for D-PAD down on a controller, or SHIFT on a keyboard

### NPC Settings

Uncheck _NPC Dodge AI_. My followers have been known to get stuck in midair with this option enabled.

## All done!

Be sure to press **F9** for a last second save in case something bad happens. You _do not_ want to do these MCMs again. There are two options to start your game. The first is to talk to the Mara statue for a more traditional method. Sexy starts (most of the time involving you being naked) are available from the bookshelf nearby.