- [Licentia Configuration](#licentia-configuration)
- [Setting your resolution](#setting-your-resolution)
- [An additional note on BodySlides](#an-additional-note-on-bodyslides)
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
  - [SexLab](#sexlab-2)
  - [SAVE AND LOAD!](#save-and-load)
  - [SL Anim Loader](#sl-anim-loader)
    - [General Options](#general-options)
  - [A Matter of Time](#a-matter-of-time)
  - [AGO](#ago)
    - [Settings](#settings)
  - [BBLS](#bbls)
  - [CGO](#cgo)
    - [Settings](#settings-1)
  - [Clockwork](#clockwork)
  - [Deadly Dragons](#deadly-dragons)
  - [Diverse Dragons Col. 3](#diverse-dragons-col-3)
  - [Extended UI](#extended-ui)
  - [Follower Framework](#follower-framework)
    - [System](#system)
  - [GIST Soul Trap](#gist-soul-trap)
  - [Growl Werebeasts](#growl-werebeasts)
  - [Immersive Creatures](#immersive-creatures)
    - [Creature Toggles](#creature-toggles)
    - [Additional Spawns](#additional-spawns)
  - [Quick Light](#quick-light)
  - [Sacrosanct Vampires](#sacrosanct-vampires)
  - [Serio's Hotkeys](#serios-hotkeys)
  - [SexLab Aroused](#sexlab-aroused)
    - [Settings](#settings-2)
  - [SexLab Eager NPCs](#sexlab-eager-npcs)
    - [General](#general)
  - [SexLab Solutions](#sexlab-solutions)
    - [follower](#follower)
  - [SexLab Tools](#sexlab-tools)
    - [Settings](#settings-3)
  - [SKY UI](#sky-ui)
    - [General](#general-1)
  - [SmoothCam](#smoothcam)
    - [Presets](#presets)
  - [SPERG](#sperg)
  - [SSoB](#ssob)
  - [Storm Lightning](#storm-lightning)
    - [presets](#presets-1)
  - [The Ultimate Dodge Mod](#the-ultimate-dodge-mod)
    - [NPC Settings](#npc-settings)
  - [Trade and Barter](#trade-and-barter)
  - [Wildcat Combat](#wildcat-combat)
  - [Ashes](#ashes)
- [All done!](#all-done)

## Licentia Configuration

## Setting your resolution

_Licentia Cash Money_ has been configured to run at _1920x1080_ by default. This not only ensures higher FPS, but also quick turnaround for the various "animations" which are laggy in the best of situations. If you wish to change this to a higher resolution, bear in mind that you _will not_ get 60FPS at 4k and most likely not at 1440p. In any case, click the hammer and gear icon and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. (Should be under [Display] which is itself in alphabetical order.) Change the values for _iSize H_ and _iSize W_ to the resolution you wish. Below are some common resolutions you can use.

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/1778). Install it as you would any other Mod Organizer mod. Just put it under _Added Mods._

I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## An additional note on BodySlides

With the addition of Creation Club armors you need to build them for your body. Go back to the BodySlides readme and make sure that, along with _3BBB_, you also select _CBBE Creation Club Outfits Immersive (Non HDT and HDT) and _Divine Crusader CBBE_. Follow the rest of the directions as written.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard).  There are no presets for Argonians and Khajiits for some reason. I made two male presets, a mage and a warrior, with an (M) after the name. Keep in mind that if you choose a _male elf_ character, the facial hair will look weird unless you switch the _Face Part_ to **3.** You'll know you have the right one when it says "high poly" in the bottom right and the face suddenly looks 10,000 times more detailed. Tweak to your liking, you might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Experiment and figure it out. One thing you can do is open the console with the _Tilde `_ key, click on yourself, and type _unequipall_, and then reload your preset to go nude. Click _Done_ (in the lower left) when you are finished.

**IF YOUR BODY TURNS PURPLE**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

You will get a **POPUP** from "The Curators Companion". Answer Ok and **DO NOTHING** until you get another popup. Click _Scan Later_. After a third popup, you should be ready to continue.

## A bit of a note on System Settings

### Controls

The controls for "Licentia" have been set to mouse and keyboard by default, due to the addition of a sprint-slide mod that I love. If you wish to use a controller, please be certain to **delete** any _ControlMap_Custom_ files in your Skryim **game* directory if you plan to do so. Note that you will have to bind any keyboard controls again (such as QuickSave / QuickLoad)

Unfortunately 8-way dodges are not possible with a controller without an external program and forcing "always run" which is esssential to any type of Sneak. As you play, keep in mind that you can roll or step dodge in only the four cardinal directions. Sneak / Dodge is on "B" (Like Dark Souls). You can switch between the step dodge and a roll with the G key. The menu is weird, "Start" opens the system and quest menu "RB + Start" opens the "TweeN" menu (skills / magic / items / map). Lock on is set to "LB." Where _CGO_ really shines is with a two-hander in one hand and a spell in the other, so fire up those spellsword builds! Don't forget you can also _attack while jumping_ for "death from above" or fancy archery tricks. All melee attacks are "unlocked" which means you can move freely while executing them to land the perfect mace to the dome no matter how squirrelly your opponent.

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

#### Install

Under **SexLab 1.63 SE dev beta 8 by Ashal@LoversLab.com**

Click _INSTALL/UPDATE SEXLAB 163 SE DEV BETA 8_

Close the menu and wait. Once again, a series of messages will appear in the upper left corner. 

Do not touch the mouse or keyboard until the following message appears:

**SexLab - SexLab v1.63 SE dev beta 8 - Ready!**

Then open the MCM and continue.

### SexLab

#### Sex Diary / Journal

Your character is considered heterosexual by default. If you wish to change this, under **Sexual stats** on the right, click _Sexuality_ until your preference (Bisexual, Gay, or Lesbian) appears.

####  Rebuild & Clean

Just below **Debug / Development Mode** in the upper right corner, click _Import Settings: Click Here_

A message will appear which concludes with "Do you want to continue?" Click _Accept_

Another message will appear, "SexLab configuration successfully imported." Click _Accept_

I have removed all Futa options because I am not into them. Remaining are seven strapons of varying ridiculousness. If you don't want them click on each one until none are left.

If you do want your females to sometimes use strapons, navigate to

#### Animation Settings

and click the mark on the right that reads _Females Use Strap-ons._

Note that **ALL** of _SexLab's_ original old animations have been suppressed due to unpopularity. If you want to re-enable them for some reason, click _CLEAR SUPPRESSED LIST - CLICK HERE_

### SexLab

### SAVE AND LOAD!

Lover's Lab recommends saving and loading the game immediately after fully configuring SexLab. Please do so now. If the QuickSave and QuickLoad buttons have changed, recall that they are now _F9_ and _F10_.

###  SL Anim Loader

#### General Options

Click _Enable All: Click Here_

Click _Register Animations_

The process will take about two minutes, whereupon you will receive a message that animations have been registered. Just click _Accept_

### A Matter of Time

Load the User Preset.

### AGO

#### Settings

Under **Enable/Disable** deselect _Persistent Arrows_.

### BBLS

This is the cash money suite. There are a lot of options here that are really personal preference. I recommend you look over the descriptions and enable the ones you are interested in. 

A bit of a note, the options under **Resource Heavy** may have a significant impact on Papyrus load. I haven't tested them extensively and make certain to leave them disabled in more heavily scripted profiles. However, they are quite fun.

###  CGO

#### Settings

_Unlocked Grip_

Change the _Hotkey_ to **Z** if you use M+KB and **D-PAD LEFT** if you use a controller.

_Grip Notifications_

Uncheck _NPCs Change Grip_.

Scroll to the bottom

_Dual Wield Blocking_

Set to **Mouse 3 (Scroll Wheel)** for M+KB and **RB** for controller. This function will be duplicated with "Sprint" on the latter.

_Unlocked Movement_

Make certain all options are unchecked.

Scroll to the top

_Dodge Roll_

Change _Input Type_ to **HOTKEY (TAP)**. This effectively disables CGO's dodge.

_Leaning_

_Lean Multiplier (1st Person)_: _X0.00_

_Lean Multiplier (3rd Person)_: _X1.00_

_Camera Noise_

_Camera Noise Mult (1st Person)_: _X0.00_

### Clockwork

The respawn on the Gilded gets a little excessive at default. If you want to hate the Clockwork mod, leave these settings alone. If you want to respect it, set _Gilded Recovery Time_ to **6 Hours**. If you want it to be a walk in the park, disable the recovery.

### Deadly Dragons

Uncheck _Knockdown_.

### Diverse Dragons Col. 3

A word of warning, the dragons _Nether_, _Sanguine_, and _Vile_ have been reported to be _extremely_ unfair and difficult to kill. I recommend unchecking them under **Dragons**. You will need to close the menu and wait for the announcement.

### Extended UI

Check _Show Attribute Modifiers_ and _Show Skill Modifiers_

###  Follower Framework

####  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

### GIST Soul Trap

Check _Show message on soul trapped_.

### Growl Werebeasts

Check _Invulnerable During Transformation_

### Immersive Creatures

#### Creature Toggles

Disable _Goblins_ on the right.

#### Additional Spawns

**Spawn Types**

Disable _Animal Spawns_ and _Ore Guardian Spawns_.

### Quick Light

Set _Type of Light Source_ to **No Special Effect**

Set the brightness to _Bright_ if you want to preserve most of the lighting's integrity.

If you're more concerned about being able to see well, set it to _Wide_ and use it sparingly.

### Sacrosanct Vampires

Check _Fortitude: Disable_

### Serio's Hotkeys

Recommend _Use Vanilla Hotkeys_ if you're on controller.

You'll have to read about the mod if you wanna use it, I'm still experimenting. Basically you can set it so your hotkeys are a function of shoulder button + face button for a total of 8 hotkeys on the controller (kinda like FF14 if you've ever played that on console)

###  SexLab Aroused

#### Settings

Scroll to the bottom.

Put checks in the following: _Purge Dead Actors Every 10 Game Days_, _Require Light of Sight for arousal_, _Require naked actors to change arousal._, and _Enable SOS_. These options are more realistic but previously impossible in the original version of SLA. Now that most of the script load has been shunted to SKSE they can be safely enabled, and you may notice the update time on arousal is now 30 seconds instead of 300. Another nice feature of SLAM-SE is that your arousal doesn't skyrocket for no reason all the time. It is also much easier to keep low.

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

### SexLab Tools

#### Settings

_Matchmaker queue_

**Matchmaker queue key**: set to _NUMPAD 2_

Ignore the message that the key is already mapped and answer "Yes."

**Please Note**: You can hover your crosshair over any person and press _NUMPAD 2_ to set up a sex scene at any time with any animation without any consequences. Please note that the person in the _receiver_ slot is always the "bottom" in a sex scene. Every other slot is an _actor_ and will primarily have sex with the receiver although sometimes it varies. 

To add yourself to a slot, hover your crosshair over empty space and press _NUMPAD 2_. Then select the slot you want to participate in. Each time you place somebody in a slot, you will have to choose several options. _Set with animation_ obviously, then the type of animation you want. 

Finally you'll have to type in how many total people will be in the scene. And yes, you have to do this _every time you add somebody_. It's not the best. 

Here's what makes up for it though, after you begin the scene by clicking on empty space and choosing _Begin scene_, you can press the _Shift+H_ keys to select from a list of commands, including changing positions, stages, and choosing animations from a list. Remember, it only draws from the first 250, or the first 250 of whatever tag you set. If your tag is too specific, nothing will be in the list.

### SKY UI

#### General

Set _Font Size_ to Small.

Disable the _Active Effects HUD_. (It gets in the way of my AMOT preset.)

### SmoothCam

#### Presets

Click on _Slot 1: Souls-Like_ under _Load Preset_ **ON THE RIGHT SIDE** and wait for the message.

IF YOU ACCIDENTALLY CLICK IT UNDER SAVE, you are screwed for now.

Close the game and reinstall the mod _Souls-Like SmoothCam Preset_ with a right click. 

Then reload the game and return to this menu and pay more attention!

### SPERG

Click _Enable Salvage_

Turn on Quest Rewards.

Enable _Staff Leveling_

### SSoB

Enable _Quest Markers on Stones of Berenziah_

### Storm Lightning

#### presets

Click _Realistic_ and wait for it to say **DONE**

### The Ultimate Dodge Mod

#### NPC Settings

Uncheck _NPC Dodge AI_. My followers have been known to get stuck in midair with this option enabled.

### Trade and Barter

This is a bit of personal preference but I recommend leaving it off. It's in here to make speech buffs more rewarding, which you can do by clicking _Modify Barter Settings_ and setting the _Barter Preset_ to **MEDIUM**. I'm warning you though, it'll make it really hard to keep your followers paid and you can probably forget about building a Hearthfires home.

### Wildcat Combat

Check _Disable Dynamic Combat_.

Enable _Allow Wildcat to Manage Difficulty_

This is mainly in here to buff melee and give more variety to the difficulty levels.

Speaking of which, Licentia is set to _Expert_ by default, which is more of a balance, but _Adept_ lets you feel like more of a hero and _Master_ is more of a challenge. _Legendary_ is a touch too hard unless you like running away most of the time or rolling with a full posse.

### Ashes

All you need to do is enable the mod.

## All done!

Be sure to press **F9** for a last second save in case something bad happens. You _do not_ want to do these MCMs again. There are two options to start your game. The first is to talk to the Mara statue for a more traditional method. Sexy starts (most of the time involving you being naked) are available from the bookshelf nearby.
