- [Licentia Configuration](#licentia-configuration)
  - [Setting your resolution](#setting-your-resolution)
  - [Customizing Controls](#customizing-controls)
  - [Using A Controller](#using-a-controller)
  - [Disabling NSFW Features](#disabling-nsfw-features)
  - [Character Creation](#character-creation)
  - [AS SOON AS CHARACTER CREATION IS COMPLETE](#as-soon-as-character-creation-is-complete)
  - [Game MCM Options](#game-mcm-options)
  - [Fertility Mode+](#fertility-mode)
  - [OStim](#ostim)
    - [How To Use This Mod](#how-to-use-this-mod)
  - [Quick Light](#quick-light)
  - [Skyrim Outfit System](#skyrim-outfit-system)
  - [VioLens](#violens)
  - [Now you are ready to spawn!](#now-you-are-ready-to-spawn)
  - [FINAL NOTE: On Alternate Starts](#final-note-on-alternate-starts)

# Licentia Configuration

## Setting your resolution

_Licentia_ has been configured to run at _2560x1440_ by default. If you wish to change this to a higher or lower resolution, click the "Tools" icon above the list of mods and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. 

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, there may be steps you can take such as reinstalling the _Dear Diary_ series of mods, but these are **unsupported** because I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

## Customizing Controls

The vast majority of these options are configured in the "Controls" portion of Skyrim's pause menu. Please take note that your "Sneak" key is **NO LONGER SNEAK**, it is **DODGE** instead. If you wish to select a sneak key, first configure your **DODGE** key (which is labeled as **SNEAK** in the "Controls" menu, remember). Then open the MCM and choose the _Ultimate Dodge_ option. There is an entry there for "Sneak Key", click it and choose. In the end I think you will be better served with Dodge as _Shift_ and Sneak as _CTRL_.

To change the _Quick Light_ key, open the _Quick Light_ MCM and you should see the option. The same is true for _CGO_, there are options for _Grip Shift_ and _Dual Wield Blocking_.

The last control you need to configure is within the _True Directional Movement_ mod. I recommend setting the "Lock-On" key to one of your alternate mouse buttons, such as the scroll wheel or one of the side buttons, if you have one.

## Using A Controller

Due to incompatibilities with _OStim's_ FreeCam I have disabled all controller mods by default. They can be found under "Controller Options", but serve no purpose so long as you use a mouse and keyboard. However, if you wish to play with a controller, you will have to **enable all these mods** and **delete any ControlMap_Custom" file(s) in your Skyrim game directory.** _If there is no such file in your Skyrim directory, you do not need to worry about it._ Just make certain one is not present.

You will have to configure CGO (I recommend D-Pad Left for grip shift and LB or L1 for Dual-Wield Blocking), The Ultimate Dodge Mod (I recommend D-Pad Down for Sneak), and Quick Light (I recommend D-Pad Up). There is no good button for lock-on, I typically assign the same one as Spring and Dual-Wield Blocking (LB).  Finally, reconfigure your QuickSave and QuickLoad keys in-game. You must ALSO recall that almost ALL OStim navigation can only be accomplished via the keyboard, so you will have to either switch back and forth or set to autopilot. When all is said and done the Gamepad controls will be as follows:

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

## Disabling NSFW Features

A handful of mods in this list contain sexual content that may be a bit too "raw" for some players, namely _Amorous Adventures_ and _OStim Solutions_, which feature potentially disturbing content including graphic depictions of outlandish fetishes and/or non-consensual sex, and especially _OProstitution,_ which encourages sex work. However I have gone out of my way to alter them so that all of them are optional and/or clearly marked as offensive. None of this content will be "sprung" on you without your consent. 

You may also wish for the sex part of the list to be completely optional. While you cannot remove the adult dialog options without reworking most of the list, you **can** ensure that any pornographic imagery only takes place when you choose for it to. Somewhere inside your load order is an ESP called "ONights." This ESP enables NPCs in the game to have sex with each other on their own without your input. Once again, you must disable it **ONLY BEFORE CHOOSING NEW GAME.** Doing so at any other time will cause issues. 

Still want to sleep your way around Skyrim without straight up watching porn? Thanks to my users, I have an option for that now as well. In addition to the above options, simply enable the _OFadeToBlack_ mod in its corresponding MCM menu, and disable the stripping of _Slots 49 and 56_ in the _OStim_ "Undressing" MCM section. This will cause the screen to Fade To Black every time a sex scene begins, so you can still get the easier quest rewards and the degradation of being attractive and easy, without actually offending any onlookers. If you do select this option, you will also need to disable the OAroused mod, or these scenes will _never end._ In addition, if you get stuck in a scene, you can press the NUMPAD Decimal key to escape it.

As far as I know, if you configure everything listed above, there will be absolutely no sex or nudity in your list except for a few randy dialog options. I offer no bulletproof guarantees, though, so be careful. Keep in mind the strong warning at the beginning of this readme still applies.

I do have a bit of a warning here however. Although distribution is rather rare, there are still a few skimpy outfits sprinkled throughout the list. I enabled this option because it is one of my most commonly requested features, and I also enjoy seeing a nice sexy outfit now and again myself. To be more specific, the Khajiit caravans sell extremely slooty armors from _BD's Armor Replacer_ (which are basically bikinis from _TAWOBA_) and some of the skimpier outfits from _The Book of UUNP_ can sometimes be found on NPCs. I wished to make them only craftable or purchasable, but it is a great deal of work due to the hundreds of outfits and the deliberate, spaghetti-like nesting of some of the leveled lists.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A or AL - Altmer, AR - Argonian, BO - Bosmer, BR - Breton, D - Dunmer, I - Imperial, K - Khajiit, N - Nord, O - Orsimer, R - Redguard). Many of these faces also come with a "Sculpt" as well, so click the _Sculpt_ menu and import the `NIF` that matches your preset.

Tweak to your liking, but bear in mind that many of the close-cropped hairstyles will **NOT** look right until you select the _High Poly Head_ by navigating to the _Head_ portion of RaceMenu and choose _Face Part 3_ (near the bottom). You might enjoy some of the _SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. 

It used to be possible to tweak your body with _Morphs_, however _OBody_ has made short work of that. If you wish to customize your body, I recommend using the _BodySlide Studio_ Tool to create and save your own "Preset". Google will be of assistance here, as will visiting one of my support channels on Discord. Adjusting the schlong with _Genitals_ should still work, although you'll have to close _RaceMenu_, take off your clothing, and use the Vanity Mirror. Don't go too baby arm with it or it'll go straight through people!

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

**DO NOTHING** until **ALL** of the messages in the top left corner stop appearing. This is the most script intensive part of the game and may break otherwise. 

Fertility mode will pop up a window requesting to turn on. Choose NO right now, even if you want it on, as the script load can get too high.

## Game MCM Options

**NEW!** This section is now Deprecated. Run the DEFAULT MCM Recording from the MCM Recorder MCM Menu. There are also a few difficulty and adult options for you to choose. This modlist will NOT function unless you run this default recording.

## Now you are ready to spawn!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. I have expanded roleplaying options from the beginning of the game with the mod "Abandoned Prison Tweaks." First turn around and grab the key and mirror on the shelf nearby. The mirror is what you should use to change your appearance -- it causes far fewer bugs than the ``showracemenu`` command. The book provides a little flavor text on how you got where you are. The key opens the cabinet nearby, which you should do now. Inside you will find many books. On the left are alternate starts that usually put you somewhere compromised and naked. Underneath is "The Firmament", a book that lets you choose whatever Standing Stone you prefer from the beginning. On the right is a chest with scrolls to assign your starting spells -- take all of them if you are a power gamer, or only the ones that represent your background. On the middle shelf is another key, which you should grab, and a cask with a few potions in it. On the bottom shelf is a chest with various crappy starting gear you can wear. There are two ways to choose where you will spawn. The statue, as in most lists, provides a host of specfic roleplaying options. And of course, there are the books mentioned previously. Do note that you must PICK UP a book to choose the start, not just READ it. After choosing one, check the small chest hidden behind a barrel in the corner where you started for a dozen lockpicks if you wish to take them. Then sleep on the bed to begin. 

## FINAL NOTE: On Alternate Starts

Arthmoor's official position on his Alternate Start mod is that, in order to ensure that the Main Quest and any other mods or quests relying upon it work correctly, at some point early in the game you must make your way to Helgen and walk through all of the quest triggers located therein just as though you had played through the Alduin attack. This means going inside the keep, making your way down to see the roof collapse, running up against the blocked passage, THEN backtracking out of the keep, finding the cave entrance marked by the Unbound quest chain, and encountering Ralof and Hadvar inside so you can choose a "side" for any Civil War content you choose to partake in. I am confident this is necessary in most cases because I have had confirmed reports of quests breaking for my users if they chose an Alternate Start and skipped these steps. While not necessary for a limited roleplaying character (like say, a grimdark stealth archer who only does the Thieves' Guild and Dark Brotherhood questchains), if you wish to complete a "long playthrough" of Skyrim you **MUST** make it a point to traipse through Helgen and down to Riverwood before you do much else. Sorry but them's the breaks.
