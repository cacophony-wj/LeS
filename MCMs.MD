- [Licentia Configuration](#licentia-configuration)
  - [Setting your resolution](#setting-your-resolution)
  - [Customizing Controls](#customizing-controls)
  - [Using A Controller](#using-a-controller)
  - [Enabling POV Sex](#enabling-pov-sex)
  - [Enabling SFW Features](#enabling-sfw-features)
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

_Licentia_ has been configured to run at _1920x1080_ by default. If you wish to change this to a higher or lower resolution, click the "Tools" icon above the list of mods and choose _INI Editor_. Now search the _SkyrimPrefs.ini_ for a line that begins with _iSize_. 

"1080p" is _iSize H = 1080_ & _iSize W = 1920_
"1440p" is _iSize H = 1440_ & _iSize W = 2560_
"2160p" or "True 4K" is _iSize H = 2160_ & _iSize W = 3840_

If you have an Ultrawide monitor, you will need to enable all of the mods in the "UltraWide" section of the modlist. I can't help you get it working or test problems with it because I don't have Ultrawide. You can always refer to other Wabbajack readmes or drop by Discord and type _!usesearch_ to hunt for other users' experiences.

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

## Enabling POV Sex

One of the most fantastic developments of the entire _OStim_ suite, in my humble opinion, is the ability to have almost completely clippingless first person POV sex. It is extremely immersive, but to be quite honest, the _Improved Camera_ mod it relies upon to function (which gives the player a first person body) has so many bugs and unusual quirks that it necessitates a great deal of additional "tech support," so I have chosen to disable it by default. If you wish to have sex in first person, you can feel free to enable this mod **and its INI** in the relevant "Camera" section of MO2, with the following caveats:
 
1. To have POV sex, you must begin the scene in first person
2. You must remain in first person throughout the entire scene, switching to 3rd and back can cause bugs
3. The vanilla Skyrim intro (cart ride) will not function correctly, choose an alternate one
4. There will be more flicker on mountains and distant textures
5. Distant pop-in may be worse
6. Camera switching may be buggy and/or inconsistent, press F a few times to fix it
7. You may no longer be able to switch cameras with the scroll wheel, use the F key instead
8. You may get locked up or frozen into neverending crafting, mining, wood-chopping animations, and finally
9. Sometimes you will be able to see your headless body running out ahead of you.

The sex is great though!

## Disabling NSFW Features

A handful of mods in this list contain sexual content that may be a bit too "raw" for some players, namely _Amorous Adventures_ and _OStim Solutions_, which feature potentially disturbing content including graphic depictions of outlandish fetishes and/or non-consensual sex, however I have gone out of my way to alter them so that all of them are optional and/or clearly marked as offensive. If you wish to avoid them, please do not select any dialog options with a "disturbing content" warning.

The modlist is also extremely easy to customize to prevent almost all graphic sexual content. If you're like me, you may have a thing for fancy underwear. You may also wish for the nudity in this list to be minimized, or all of the sex stuff to be optional, perhaps because you are playing in mixed company, around your younger (or older) family, or you just don't want the embarrassment of somebody watching you play a video game with tits and schlongs in it. As a friend to personal shame myself, I understand completely. 

At the end of your load order you will find an "Undies" ESP. For all characters to be equipped with a lootable pair of Undies, simply enable this ESP before choosing "New Game." This is the **ONLY** time that this ESP can be enabled or disabled -- before you choose "New Game." To do **AT ANY OTHER TIME** will cause all kinds of wardrobe malfunctions including missing inventory and naked people walking around. This is also true if this Undies ESP is ever updated, and I do have to do that sometimes. You have been warned!

You may also wish for the sex part of the list to be completely optional. While you cannot remove the adult dialog options without reworking most of the list, you **can** ensure that any pornographic imagery only takes place when you choose for it to. Somewhere inside your load order is an ESP called "ONights." This ESP enables NPCs in the game to have sex with each other on their own without your input. Once again, you must disable it **ONLY BEFORE CHOOSING NEW GAME.** Doing so at any other time will cause issues. 

Still want to sleep your way around Skyrim without straight up watching porn? Thanks to my users, I have an option for that now as well. In addition to the above options, simply enable the _OFadeToBlack_ mod in its corresponding MCM menu, and disable the stripping of _Slots 49 and 56_ in the _OStim_ "Undressing" MCM section. This will cause the screen to Fade To Black every time a sex scene begins, so you can still get the easier quest rewards and the degradation of being attractive and easy, without actually offending any onlookers.

As far as I know, if you configure everything listed above, there will be absolutely no sex or nudity in your list except for a few randy dialog options. I offer no bulletproof guarantees, though, so be careful. Keep in mind the strong warning at the beginning of this readme still applies, and if you enable or disable any mods (as opposed to making MCM changes), **do not ask for assistance from Wabbajack support staff.** Keep it only to my private server, please.

I do have a bit of a warning here however. Although distribution is rather rare, there are still a few skimpy outfits sprinkled throughout the list. I enabled this option because it is one of my most commonly requested features, and I also enjoy seeing a nice sexy outfit now and again myself. To be more specific, the Khajiit caravans sell extremely slooty armors from _BD's Armor Replacer_ (which are basically bikinis from _TAWOBA_) and some of the skimpier outfits from _The Book of UUNP_ can sometimes be found on NPCs. I wished to make them only craftable or purchasable, but it is a great deal of work due to the hundreds of outfits and the deliberate, spaghetti-like nesting of some of the leveled lists.

## Character Creation

Creating a face is very time consuming so I have included many presets. Use your mouse to click the _Presets_ button in the upper right, choose _Load Preset_, and experiment with the options. Make sure your race matches the race of the preset (A or AL - Altmer, AR - Argonian, BO - Bosmer, BR - Breton, D - Dunmer, I - Imperial, K - Khajiit, N - Nord, O - Orsimer, R - Redguard). Many of these faces also come with a "Sculpt" as well, so click the _Sculpt_ menu and import the `NIF` that matches your preset.

Tweak to your liking, but bear in mind that many of the close-cropped hairstyles will **NOT** look right until you select the _High Poly Head_ by navigating to the _Head_ portion of RaceMenu and choose _Face Part 3_ (near the bottom). You might enjoy some of the _SMP_ hairs in the rightward section of the _Hairs_ slider, they have physics which probably won't work until character creation is complete. 

It used to be possible to tweak your body with _Morphs_, however _OBody_ has made short work of that. If you wish to customize your body, I recommend using the _BodySlide Studio_ Tool to create and save your own "Preset" and then assigning it as described in the "Female Bodies" portion of the main readme. Google will be of assistance here, as will visiting one of my support channels on Discord. Adjusting the schlong with _Genitals_ should still work, although you'll have to close _RaceMenu_, take off your clothing, and use the Vanity Mirror. Don't go too baby arm with it or it'll go straight through people!

**IF YOUR BODY OR FACE TURN PURPLE OR OTHERWISE WEIRD**, scroll Racemenu over to _Body Paint_ and make sure all Textures are set to _Default_ (press the "T" key)

## AS SOON AS CHARACTER CREATION IS COMPLETE

**DO NOTHING** until **ALL** of the messages in the top left corner stop appearing. This is the most script intensive part of the game and may break otherwise. (It almost certainly will break if you forgot to copy game folder files.)

Fertility mode will pop up a window requesting to turn on. Choose NO right now, even if you want it on, as the script load can get too high.

## Game MCM Options

**NEW!** Almost every MCM is now automated! The only two mods you may be interested in configuring are _Fertility Mode_ and _Ostim_ itself. Read on for details!

## Fertility Mode+

"Enable" the mod. This is a _slow_ process. It will lock up the MCM menu, most likely, so you will have to exit all menus and re-enter.

Check _No Non-Unique Women_ and _No Non-Unique Men_.

You may also be interested in the "Automation" options in the lower right.

The _Spouse Fidelity_ option is hilarious if you set it down to around 50%. This basically means you have more baby mama drama than an Oklahoma trailer park.

_Randomly Inseminate_ allows you to simulate widespread fucking without acting it out. Be wary of this mode!

Finally, the default feedback is a bit intrusive. I recommend switching to _Page 2_ of the settings and disabling _Verbose Messages_ and _The Widget._ Otherwise, you will receive messages about insemination and, if you are female, have a really anatomical depiction of your reproductive organs onscreen at all times. I don't want to talk about it.

## OStim

The settings in this extensive mod are almost all down to personal preference. I recommend you simply "Import Settings" to get my recommendations (scroll all the way down, on the right). If you wish to customize the settings further, I recommend you read about the whole Suite of mods on Nexus. It's pretty cool stuff.

### How To Use This Mod

OStim/OSex is a little tough to get used to but the gist is that you use 8,4,5, and 6 on the NUMPAD like another set of WASD keys to move around in the OSex menus. 7 chooses a command, 9 swaps actors or functions, 1 cancels a command. + is inspect or advance scene, enter is open or close menu. Period or decimal ends the scene. Freecam is now enabled, but not automatically. Press the forward slash key on the NUMPAD to activate it.

Personally as a despicable Boomer and former data entry clerk at UPS, the fact that people willingly choose to do without NUMPADs both disturbs and angers me. But I know it's a thing. If you don't have one, no problem. You can hold down **F8** for 10 seconds to rebind all of OSex's default controls. Good luck finding keys that aren't already in use.

If you encounter a scene that is terribly out of alignment, press the L key to open a menu with tons of options for adjustments (this is the OAlign mod). If you save your changes they will persist for that animation.

At any time you can go up to anyone and press the up arrow to have OSex sex with them. **NOTE: DO NOT INITIATE SEX WITH THE STANDARD OSA MENUS!** (Available via the ENTER key on your numpad.) _OStim_ overrides these, so they will not function.

Creatures do not function with OSex and I have no plans to ever implement them.

## Quick Light

Just as a note here, the free lantern can be turned on at any time by striking the `L` key or holding down the `Activate` button (`E` on keyboard, `A` on Gamepad). The keys for this can be changed in this MCM, as well as the brightness and style of the lantern.

## Skyrim Outfit System

This section is brought to you entirely by my devoted user `Palentier` who was convinced someting was wrong with this mod, prompting me to remove it, pissed off half my server, then made amends by realizing his mistake and writing this guide. Thanks a lot, man!

This mod allows you to have multiple outfit appearances that can be saved, favorited and switched or removed totally with the "Change Outfit" power. This mod allows you to wear any Armor including shields and jewelry while maintaining the appearance of the set you saved.  So you can get your Characters Look exactly how you want it, while wearing the stuff you need to buff your character with.

Using this Mod is optional, but you MUST use the "Change Outfit" Power and select [NO OUTFIT] if you wish to see your character nude for Ostim scenes.  This power can be used after starting the scene if you forget to turn it off before the scene begins.  WARNING: The setting under Outfit settings (while creating a new Outfit) "Require Equipped Armors" **WILL NOT REMOVE YOUR UNDERWEAR.**  You must manually select [NO OUTFIT] each time you start a scene.

### Options

**Quick Slots Enable**

_You must Favorite an Outfit to see it in the Change Outfit Power Menu_

## Now you are ready to spawn!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. I have expanded roleplaying options from the beginning of the game with the mod "Abandoned Prison Tweaks." First turn around and grab the key and mirror on the shelf nearby. The mirror is what you should use to change your appearance -- it causes far fewer bugs than the ``showracemenu`` command. The book provides a little flavor text on how you got where you are. The key opens the cabinet nearby, which you should do now. Inside you will find many books. On the left are alternate starts that usually put you somewhere compromised and naked. Underneath is "The Firmament", a book that lets you choose whatever Standing Stone you prefer from the beginning. On the right are Prostitution starts -- which are for flavor text only so far. Behind these books (move them by holding down the Activate button) is a chest with scrolls to assign your starting spells -- take all of them if you are a power gamer, or only the ones that represent your background. On the middle shelf is another key, which you should grab, and a cask with a few potions in it. On the bottom shelf is a chest with various crappy starting gear you can wear. There are two ways to choose where you will spawn. The statue, as in most lists, provides a host of specfic roleplaying options. And of course, there are the books mentioned previously. Do note that you must PICK UP a book to choose the start, not just READ it. After choosing one, check the small chest hidden behind a barrel in the corner where you started for a dozen lockpicks if you wish to take them. Then sleep on the bed to begin. 

### The Dodge Mod Will Not Work Until You Leave The Starting Cell.

### Do Not Report Bugs With The Dodge Mod If You Have Not Left The Starting Cell.

## FINAL NOTE: On Alternate Starts

Arthmoor's official position on his Alternate Start mod is that, in order to ensure that the Main Quest and any other mods or quests relying upon it work correctly, at some point early in the game you must make your way to Helgen and walk through all of the quest triggers located therein just as though you had played through the Alduin attack. This means going inside the keep, making your way down to see the roof collapse, running up against the blocked passage, THEN backtracking out of the keep, finding the cave entrance marked by the Unbound quest chain, and encountering Ralof and Hadvar inside so you can choose a "side" for any Civil War content you choose to partake in. I am confident this is necessary in most cases because I have had confirmed reports of quests breaking for my users if they chose an Alternate Start and skipped these steps. While not necessary for a limited roleplaying character (like say, a grimdark stealth archer who only does the Thieves' Guild and Dark Brotherhood questchains), if you wish to complete a "long playthrough" of Skyrim you **MUST** make it a point to traipse through Helgen and down to Riverwood before you do much else. Sorry but them's the breaks.
