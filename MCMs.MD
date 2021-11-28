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
    - [Configuration](#configuration)
      - [Sex Scenes](#sex-scenes)
      - [Beds](#beds)
      - [Undressing](#undressing)
    - [How To Use This Mod](#how-to-use-this-mod)
  - [CGO](#cgo)
  - [Skyrim Outfit System](#skyrim-outfit-system)
  - [Now you are ready to spawn!](#now-you-are-ready-to-spawn)

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

## Enabling SFW Features

If you're like me, you kinda like a nice pair of bloomers every so often. You may also wish for the nudity in this list to be minimized, or all of the sex stuff to be optional, perhaps because you are playing in mixed company, around your younger (or older) family, or you just don't want the embarrassment of somebody watching you play a video game with tits and schlongs in it. As a friend to personal shame myself, I understand completely. 

At the end of your load order you will find an "Undies" ESP. For all characters to be equipped with a lootable pair of Undies, simply enable this ESP before choosing "New Game." This is the **ONLY** time that this ESP can be enabled or disabled -- before you choose "New Game." To do **AT ANY OTHER TIME** will cause all kinds of wardrobe malfunctions including missing inventory and naked people walking around. This is also true if this Undies ESP is ever updated, and I do have to do that sometimes, so if you choose to play with Undies, **ONLY UPDATE THE LIST AS A LAST RESORT.** You have been warned!

You may also wish for the sex part of the list to be completely optional. While you cannot remove the adult dialog options without reworking most of the list, you **can** ensure that any pornographic imagery only takes place when you choose for it to. Somewhere inside your load order is an ESP called "ONights." This ESP enables NPCs in the game to have sex with each other on their own without your input. Once again, you must disable it **ONLY BEFORE CHOOSING NEW GAME.** Doing so at any other time will cause issues. Once this ESP is disabled, the only sex scenes that will start are the ones that you choose to do so. So save it for when Granny isn't around, alright?

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

_Be Warned:_ This mod is _very_ intrusive, with a lot of "heavy" features. If this concerns you, or you do not wish to deal with the difficulty inherent from possessing a full fertility and reproductive cycle, **do not** enable this mod, as in its current state it **can not** be fully disabled again. If this is not a concern of yours...

"Enable" the mod. This is a _slow_ process. It will lock up the MCM menu, most likely, so you will have to exit all menus and re-enter.

Check _No Non-Unique Women_ and _No Non-Unique Men_.

The only other options you may be interested in are under "Automation" in the lower right.

The _Spouse Fidelity_ option is hilarious if you set it down to around 50%. This basically means you have more baby mama drama than an Oklahoma trailer park.

_Randomly Inseminate_ allows you to simulate widespread fucking without acting it out. Be wary of this mode!

## OStim

The settings in this extensive mod are almost all down to personal preference. I recommend you simply "Import Settings" to get my recommendations (scroll all the way down, on the right).

That said, a couple more optimization options are available. 

### Add-Ons

Under **ORomance**, everyone will be bisexual unless you enable "NPC Sexualities." Then you will have to confirm their sexual orientation before you can seduce them with this mod. The **Difficulty Modifier** is quite stout at default -- you require a lot of compliments, persuasion, and gifts to convince someone to like you. It's a bit like a dating sim in this respect, which was Sairion's goal. If you _really_ want to go hard with this, you will ignore all the other sexy dialog prompts and options in this modlist until you successfully seduce someone with _ORomance_ for the first time. That would be rather immersive. Finally, if you do have sex with a special lady, you may find she is suddenly angry and will not speak with you any longer. You came inside her you dumbass. They don't like that. To prevent this, check the box here that says "NPCs are not cautious about vaginal ejaculation." Makes the most sense if you don't bother with _Fertility Mode_.

Under **ONights** you can control how often the people around you have sex. This will never happen during the day and never in a public space, people will behave semi-realistically and, on default settings, they will stop having sex and put on their clothes if they spot you peeping. You can change this here, as well as increase the horniness of all of Skyrim.

### How To Use This Mod

OStim/OSex is a little tough to get used to but the gist is that you use 8,4,5, and 6 on the NUMPAD like another set of WASD keys to move around in the OSex menus. 7 chooses a command, 9 swaps actors or functions, 1 cancels a command. + is inspect / advance scene, enter is open or close menu. Period or decimal ends the scene. 

If you encounter a scene that is terribly out of alignment, press the L key to open a menu with tons of options for adjustments (this is the OAlign mod). If you save your changes they will persist for that animation.

Bear in mind that many subjects do not have appropriate animations (such as lesbian scenes). To find these, press the backslash key \ at any time, type in a keyword, and press Enter to begin.

At any time you can go up to anyone and press the up arrow to have OSex sex with them.

Creatures do not function with OSex and I have no plans to ever implement them.

## CGO

I lied, there's a third one, but it's relatively minor. For some reason when the Skyrim update was pushed, my scripts to disable headbobbing stopped functioning properly. To prevent headbobbing completely, you must find the "Camera Mult" setting in this MCM (on the right, about halfway down) and change it to anything, then back to zero. However, if you are using Improved Camera, sometimes your camera will get "stuck" in a super nauseating headbobbing mode where every little motion causes incredible jerkiness. To solve this issue, simply strike the F key a few times (or press in on the right stick with a controller)

## Skyrim Outfit System

This section is brought to you entirely by my devoted user `Palentier` who was convinced someting was wrong with this mod, prompting me to remove it, pissed off half my server, then made amends by realizing his mistake and writing this guide. Thanks a lot, man!

This mod allows you to have multiple outfit appearances that can be saved, favorited and switched or removed totally with the "Change Outfit" power. This mod allows you to wear any Armor including shields and jewelry while maintaining the appearance of the set you saved.  So you can get your Characters Look exactly how you want it, while wearing the stuff you need to buff your character with.

Using this Mod is optional, but you MUST use the "Change Outfit" Power and select [NO OUTFIT] if you wish to see your character nude for Ostim scenes.  This power can be used after starting the scene if you forget to turn it off before the scene begins.  WARNING: The setting under Outfit settings (while creating a new Outfit) "Require Equipped Armors" **WILL NOT REMOVE YOUR UNDERWEAR.**  You must manually select [NO OUTFIT] each time you start a scene.

### Options

**Quick Slots Enable**

_You must Favorite an Outfit to see it in the Change Outfit Power Menu_

## Now you are ready to spawn!

Be sure to make a last second save in case something bad happens. You _do not_ want to do these MCMs again. I have expanded roleplaying options from the beginning of the game with the mod "Abandoned Prison Tweaks." First turn around and grab the key and mirror on the shelf nearby. The mirror is what you should use to change your appearance -- it causes far fewer bugs than the ``showracemenu`` command. The book provides a little flavor text on how you got where you are. The key opens the cabinet nearby, which you should do now. Inside you will find many books. On the left are alternate starts that usually put you somewhere compromised and naked. Underneath is "The Firmament", a book that lets you choose whatever Standing Stone you prefer from the beginning. On the right are Prostitution starts -- which are for flavor text only since the OStim Prostitution mod has yet to be developed. It will get here one day, believe me! Behind these books (move them by holding down the Activate button) is a chest with scrolls to assign your starting spells -- take all of them if you are a power gamer, or only the ones that represent your background. All starting spells have been removed. On the middle shelf is another key, which you should grab, and a cask with a few potions in it. On the bottom shelf is a chest with various crappy starting gear you can wear. There are two ways to choose where you will spawn. The statue, as in most lists, provides a host of specfic roleplaying options. And of course, there are the books mentioned previously. Do note that you must PICK UP a book to choose the start, not just READ it. After choosing one, check the small chest hidden behind a barrel in the corner where you started for a dozen lockpicks if you wish to take them. Then sleep on the bed to begin. 
