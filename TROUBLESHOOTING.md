##  Troubleshooting

## Technical

### Why do I have to CTRL-CLICK to build _BodySlide_?

_Mod Organizer 2_ does not put edits to existing files in the _overwrite_ folder, only newly created files. _CBBE_, _3BBB_ and _BD_ come with "default" meshes that will be changed by _BodySlide_ if you do not direct them to the proper directory yourself. Likewise, _Nemesis_ edits all the animation source files when it updates instead of putting the changes in the overwrite folder. If you don't believe me, I encourage you to check _MO2_'s documentation or the _Nemesis_ closed _Issues_ section on Github. If this doesn't convince you, I encourage you to test it yourself.

### I tried to wear a piece of gear but my body disappeared!

If you are male, there are no male models for _Devious_ equipment in this list. They will all be invisible. I encourage you to refer to [MCMS](https://github.com/cacophony/LeS/MCMs.MD) for tips on setting up a game for a male character.

If you are female, the _Devious_ equipment is invisible unless _BodySlide_ is fully run. Follow all the steps in the [Female Bodies and Outfits](https://github.com/cacophony/LeS/BODYSLIDE.md) section.

### Some of me is too _jiggly_! (Especially the belly.)

I tried to minimize it as much as possible, but the available CBPC presets are kinda not ideal. Either reinstall the _CBBE 3BBB_ mod (position 256) and experiment with the CBPC options or install _Sinful CBPC_ (Google it) for fine control. Load order shouldn't matter, but if the MCM won't appear, open the console and type _setstage ski_configmanagerinstance 1_ and wait for the message(s).

### I read a skill book but my skill didn't go up!

This is because you "can't concentrate" if you're horny, so you don't get 100% skill experience from skill books. Check the _Magic Effects_ tab of your _Magic_ window for **red** effects that affect experience gain. Usually they are marked **Lover's Desire**. If you're not locked up with something, alleviate that need and then read the book. If you're locked into gear and can't take care of business, I have taken a cue from _Living Skyrim_ and made picking up a book the default instead of reading it. If you want to read a book (for example Inigo or LOTD notes) without stealing them, draw your weapon first.

### I can't find my save!

Try using _Show All Saves._ Devious or Cursed Loot (one of the two) sometimes puts them in a weird place, most likely because of legacy scripts.

### CGO isn't leaning / dodging! _or_ When I go into an adult scene, I hear sounds and voices but they just stand there!

I sometimes forget to run _Nemesis_ before uploading a build. Make a comment in **#licentia-et-servitium-support** and I'll get to it when possible.

###  I did all that but the things are still just standing there, especially when I get assaulted.

_Skyrim Special Edition_ is not well supported yet by the _Lover's Lab_ community, or at least not as robustly. Most players seeking to use such content do so on _Oldrim_ or _Legendary Edition,_ which unfortunately suffers from an inferior engine as far as stability and memory management goes. _Legendary Edition_ is also not "officially" available on _Steam_ any longer, which discourages mainstream mod (and modlist) authors from supporting it. 

As such, animations triggered from the SE versions of _Defeat_ and _Cursed Loot_ seem to be called in a slightly different fashion than those from _SL Tools_, _SL Solutions_, or _SLEN_. They suffer from intolerable script lag at times, regardless of how many mods or animations are installed. I understand it's a known issue that is being worked on, but until it is resolved, you'll have to break your immersion a bit. If an animation seems stuck **and** there are no moans of pleasure, just various breathing and grunts (or silence), open the console with the tilde key (`), wait for all messages to cycle, then close the console again. You may have to repeat this process at least once.

### My arms won't go into a binder _or_ my hands are floating outside of my bindings _or_ my gag won't go in my mouth _or_ one of these is true for an NPC.

First, if you added something, remove it or rerun _Wabbajack._ If you didn't add anything, there's not much I can do. _Devious_ handling of these matters is extremely finicky in its original version on Oldrim and even more so for Special Edition. Facial Expressions in Special Edition have always been a problem and the NPC arm / invisible hands problem persists to this day no matter which version you use. If you want a more bug-free game, don't use _Devious Devices_ because this is **way** out of Skyrim's purview. IF something really terrible happens and won't stop (animations always wrong, or being trapped in something you can't see in your inventory) you basically have two options.

1. Load the game from before the bug happened.
2. If that doesn't work, rerun Wabbajack and play SexLab without Devious Devices support.

**NEVER** use the _"Safe Word" (FREE ME)_ in the _Cursed Loot_ debug menu. Find a way out of your restraints as intended instead. "FREE ME" basically forces all the scripts to terminate with console commands and will probably cause more problems than it solves. It is mainly intended for testing. If you find yourself wanting to do this very often, reconsider why you are playing this modlist.

### My body shows that I'm wearing a Devious Device, I suffer all the effects from it, but it's not in my inventory so I can't remove it!

Your device bugged out. Reload from before you got equipped with it. If you don't want these kinds of problems, don't use _Devious Devices._

### I'm just gonna use debug menus or console commands to remove stuff I don't want on me anymore.

First, evaluate if _Devious Devices_ is really something you want to play _Skyrim_ with. If it is, don't use debug menus or console commands to avoid the purpose of the mod. It only makes things worse over time. If something is so horribly bugged that you can't do anything at all about it, load your game before the problem appeared. If you find yourself doing this a lot, you probably thought _Devious_ was a cool idea for you but it really isn't.

###  I'm locked into some gear and I can't move in third person.

_Devious Devices_ doesn't like the SE version of _Immersive First Persion View_ very much. Don't disable IFPV after enabling it or you will get this bug every time you stop moving while in restrictive gear. If you were unaware of this fact, save your game, reload, and the problem should go away. Don't enable _Immersive First Person View_ while locked up unless you plan to stay in first person.

### I'm playing _Light But Kinky_ and I'm in such an incredible amount of bondage gear that I can't do anything at all!

Time to reload a save before you got into that situation. Seriously, if there were an option to prevent nested equipping of Devious Devices I would enable it. But there isn't. Not without disabling most of the hilariously meme-worthy scenarios. If you get equipped in anything extremely punishing, I recommend reloading your game if anything else really punishing gets equipped on you. Unless you just want to see how ridiculous things can get.

### Stuff is disabled. Did you forget? Or, can I enable it all, for the best of both worlds?

No. All that stuff is disabled on purpose. Most of it is for technical reasons. For example, _Cursed Loot_ shuts down all of _Eager NPCs_ functions, even if you disable _Cursed Loot_, so the two won't work together. _Light But Sexy_ is more of a mainstream list, so creatures are not enabled by default. Finally, _Defeat_ does not recognize equipped devices, so you can totally be taken advantage of straight through chastity gear in a full set.

As far as enabling stuff in _Light But Sexy_... _don't try it._ None of the Devious stuff will work because of the reasons above.

### I want creatures in _Light But Sexy_!

Thanks to a helpful user an easy way to accomplish this has been discovered. Enable _only_ the creature animations in the **INTENTIONALLY DISABLED** section, move them with the other _SexLab Animations_, and re-run _Nemesis Behavioral Engine_ from the dropdown. Ensure that all four menu options remain checked. Do _not_ reinstall any of the animation packs, or add your own, as the end result will probably be frozen animations (aka the T-Pose). Ensure that no new ESPs are enabled at the bottom of the right pane.

## Gameplay

### I was locked up in the "princess" start and something defeated me and I got teleported somewhere and the quest was completely broken! This isn't fair!

Life isn't fair and _Cursed Loot_ doubles down on that. Seriously, though, there are a couple of weird spawn areas that can be troublesome with _Animallica_ and _Immersive Patrols_. Be sure to save your game before exiting the hideout either time and hope you don't get a mob spawn nearby or at Sarethi farm.

### I can't find those damn keys in the _Light But Kinky_ "princess" start!

They are non-existent until triggered. The _hideout key_ spawns outside on a random slaver corpse after you are free from the cage. You must search every body until you find it. I will tell you that the bodies are all near the road and do not go beyond the man on the ledge on one extreme or the man in the weeds on the other, so keep checking. The _office key_ spawns when you search the body of the Slaver Boss and read the note pop-up. Search every corpse and chest in the room until you find it. If you can't find it at first, keep searching until you do. I have never had an instance where it didn't show (and I have tested it many, many, _many_ times)

### Where the hell do I go after Chloe tells me about the secret passage?

Go back out the way you came and to the cave where Ralof and Hadvar are. The main quest may break if you go through _Cursed Loot's_ "narrow passage" shortcut and the _Unofficial Patch_ makes sure to warn you about it, so I have removed that option. Go all the way back in the cave until you get to the room with the spiders, kill them (or let Chloe do it, she's a beast) and search the Imperials in there for a _Torn Note_. Read the note.

### I was bound and then defeated and then teleported somewhere and now I can't get up from the ground!

Wait 30 seconds, save, wait 30 more seconds, reload the save you just made. If this doesn't allow you to stand up, you'll have to load a game from before you were defeated.