- [Licentia Configuration](#licentia-configuration)
- [Click New Game](#click-new-game)
- [Character Creation](#character-creation)
- [AS SOON AS CHARACTER CREATION IS COMPLETE](#as-soon-as-character-creation-is-complete)
- [A bit of a note on System Settings](#a-bit-of-a-note-on-system-settings)
  - [Controls](#controls)
- [Game MCM Options](#game-mcm-options)
  - [SexLab](#sexlab)
    - [Install](#install)
  - [SexLab](#sexlab-1)
    - [Rebuild & Clean](#rebuild--clean)
    - [Animation Settings](#animation-settings)
    - [Animation Settings](#animation-settings-1)
  - [SexLab](#sexlab-2)
    - [Sex Diary / Journal](#sex-diary--journal)
  - [SAVE AND LOAD!](#save-and-load)
  - [SL Anim Loader](#sl-anim-loader)
    - [General Options](#general-options)
  - [CGO](#cgo)
    - [Settings](#settings)
  - [Follower Framework](#follower-framework)
    - [System](#system)
  - [Serio's Hotkeys](#serios-hotkeys)
  - [SexLab Aroused](#sexlab-aroused)
    - [Settings](#settings-1)
  - [SexLab Eager NPCs](#sexlab-eager-npcs)
    - [General](#general)
  - [SexLab Solutions](#sexlab-solutions)
    - [follower](#follower)
  - [SexLab Tools](#sexlab-tools)
    - [Settings](#settings-2)
  - [VioLens](#violens)
    - [Profile System](#profile-system)
- [All done!](#all-done)

## Licentia Configuration

## Setting your resolution

_Licentia_ should default to your monitor's native resolution on installation. This _will not_ be 60FPS at 4k and most likely not at 1440p. If you care more about FPS than resolution, or wish to use your own ENB, you may wish to dial the resolution back a bit. To do so, click the hammer and gear icon and choose _INI Editor_. Now search the _SkyrimCustom.ini_ for a line that begins with _iSize_. (Should be under [Display] which is itself in alphabetical order.) Change the values for _iSize H_ and _iSize W_ to the resolution you wish. Below are some common resolutions you can use.

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need [this mod](https://www.nexusmods.com/skyrimspecialedition/mods/1778). Install it as you would any other Mod Organizer mod. Just put it under _Added Mods._

I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Click New Game

You might wonder why I put something so obvious here but you'd be surprised at the questions I get. It takes longer to load Skyrim with all these textures, and if you're not on an SSD you're probably going to have a bad time.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A - Altmer, Bo - Bosmer, Br - Breton, D - Dunmer, I - Imperial, N - Nord, O - Orsimer, R - Redguard).  There are no presets for Argonians and Khajiits for some reason. I made two male presets, a mage and a warrior, with an (M) after the name. Keep in mind that if you choose a _male elf_ character, the facial hair will look weird unless you switch the _Face Part_ to **3.** You'll know you have the right one when it says "high poly" in the bottom right and the face suddenly looks 10,000 times more detailed. Tweak to your liking, you might enjoy some of the _KS SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. You can also tweak your body a bit with the _CBBE Morphs_ and _Genitals_ options, but I am not going to go into that. Don't ask me either. Experiment and figure it out. One thing you can do is open the console with the _Tilde `_ key, click on yourself, and type _unequipall_, and then reload your preset to go nude. Click _Done_ (in the lower left) when you are finished.

**IF YOUR BODY TURNS PURPLE**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

You will get a **POPUP** from "The Curators Companion". Answer Ok and **DO NOTHING** until you get another popup. Click _Scan Later_. After a third popup, you should be ready to continue.

## A bit of a note on System Settings

### Controls

The controls for "Licentia" are specifically designed for use with a controller. Please be certain to **delete** any _ControlMap_Custom_ files in your Skryim **game* directory if you plan to do so. Note that you will have to bind any keyboard controls again (such as QuickSave / QuickLoad)

If you want to use a mouse and keyboard, close Skryim and disable everything under the _Controller_ section in the left pane. 

Unfortunately 8-way dodges are not possible with a controller without an external program and forcing "always run" which is esssential to any type of Sneak. As you play, keep in mind that you can roll or step dodge in only the four cardinal directions. Sneak / Dodge is on "B" (Like Dark Souls). You can switch between the step dodge and a roll with the G key. The menu is weird, "Start" opens the system and quest menu "RB + Start" opens the "TweeN" menu (skills / magic / items / map). Lock on is set to "LB." _CGO_ is also preconfigured, _D-PAD RIGHT_ will shift your grip from one handed to two no matter which weapon you wield (hello dual warhammers) and _D-PAD DOWN_ will let you block while dual wielding. Where _CGO_ really shines, though, is with a two-hander in one hand and a spell in the other, so fire up those spellsword builds! Don't forget you can also _attack while jumping_ for "death from above" or fancy archery tricks. All melee attacks are "unlocked" which means you can move freely while executing them to land the perfect mace to the dome no matter how squirrelly your opponent.

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

#### Animation Settings

**Creature animations are completely unsupported.** If you want them download the _Dungeons & Deviousness_ modlist.

### SexLab

### SAVE AND LOAD!

Lover's Lab recommends saving and loading the game immediately after fully configuring SexLab. Please do so now. If the QuickSave and QuickLoad buttons have changed, recall that they are now _F9_ and _F10_.

###  SL Anim Loader

#### General Options

Click _Enable All: Click Here_

Click _Devious Device_ on the left. _None of these animations are installed,_ so click _Disable All_ in the upper right. _If you do not disable these your characters will stand in place rather than have a scene._ If you want serious fetish content go elsewhere, this isn't the modlist for you.

Click _Register Animations_

The process will take about two minutes, whereupon you will receive a message that animations have been registered. Just click _Accept_

###  Cathedral Weathers

Just hit _Load Settings_. The confirmation message will look a little weird, but its not a big deal.

###  CGO

#### Settings

_Leaning_

I prefer the _procedural leaning_ and _camera movement_ (also known as **head bobbing**) at X1.00, but it does cause rather severe motion sickness in some players.

**If you find uncomfortable nausea happening to you, I recommend the following values:**

_Lean Multiplier (1st Person)_: _X0.00_

_Lean Multiplier (3rd Person)_: _X1.00_

_Camera Noise_

_Camera Noise Mult (1st Person)_: _X0.00_

###  Follower Framework

####  System

In the upper right, click _Load From File - CLICK HERE_

At the message **Settings Loaded. Please exist the MCM menu to apply all changes.** click _Ok_

Exit the MCM and re-open it.

A bit of a note here. I did not alter Skyrim's vanilla difficulty in any way, aside from ensuring that dragons have new abilities and dungeons match your level each time they respawn. CGO, LOTD, ZIM's, and the abundance of gear I put in here make you ridiculously powerful. What can I say, I need to be a hero in these troubling times. :sweatboy: Anyway, you will probably have to bump up the difficulty a lot (maybe even to Legendary) if you are at all good at Skyrim. (I'm not, and I made this list so I can test it by playing it.) The problem with this method is that followers are **buffed**, not nerfed, because they're considered _not-the-player_ and everything _not-the-player_ has its damaged multiplied. Combine this with player nerfs on Legendary and you'll find that with even one follower you never get a chance to hit anything before it's all dead. The only real answer for this is to use _Nether Follower Framework_ here and under _Follower Stats_ change their damage output to its lowest value: _0.10_. They'll be mostly harmless but at least you'll have your chance to shine.

### Serio's Hotkeys

Recommend _Use Vanilla Hotkeys_ if you're on controller.

You'll have to read about the mod if you wanna use it, I'm still experimenting. Basically you can set it so your hotkeys are a function of shoulder button + face button for a total of 8 hotkeys on the controller (kinda like FF14 if you've ever played that on console)

###  SexLab Aroused

#### Settings

_General_

Check _Enable SOS_.

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

### VioLens

#### Profile System

Click _Load - Select_.

A menu will appear. Select _VioLens_ and click _Exit_.

When you get the message "Are you sure you want to load?" click _Load_.

Wait a moment. You will see some stuff cycling. Then the message

_"VioLens.VLMS" Loaded_

Press _OK_

**Ye Olde - Respawn**

Activating this mod is optional but recommended. It prevents save corruption upon death. Most of the time it will return you to the nearest city, once this is done, feel free to load your game from where you died -- all risk of save contamination will be prevented. Otherwise, make your way as you see fit. Bear in mind that sometimes the mod respawns you in place -- particularly if you spawned in a dungeon and haven't discovered any other locations.

## All done!

Be sure to press **F9** for a last second save in case something bad happens. You _do not_ want to do these MCMs again. There are two options to start your game. The first is to talk to the Mara statue for a more traditional method. Sexy starts (most of the time involving you being naked) are available from the bookshelf nearby.
