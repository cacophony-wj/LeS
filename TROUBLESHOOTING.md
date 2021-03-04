- [Updates](#updates)
  - [An update came out! It's new and shiny! What should I do?](#an-update-came-out-its-new-and-shiny-what-should-i-do)
- [Content](#content)
  - [What gives? I want creatures! Where is Cursed Loot? Where is the roleplay? This is too softcore!](#what-gives-i-want-creatures-where-is-cursed-loot-where-is-the-roleplay-this-is-too-softcore)
- [Gameplay](#gameplay)
  - [What the fuck? Mirabelle, the College of Winterhold tour guide, is wandering all over the damn place!](#what-the-fuck-mirabelle-the-college-of-winterhold-tour-guide-is-wandering-all-over-the-damn-place)
  - [What the fuck? The Civil War questline is horribly fucked up. I can't complete the Battle(s) of Whiterun / Solitude / Windhelm. People are inverting backwards off the ground. Enemies don't stop spawning. There's no Ulfric/Tullius!](#what-the-fuck-the-civil-war-questline-is-horribly-fucked-up-i-cant-complete-the-battles-of-whiterun--solitude--windhelm-people-are-inverting-backwards-off-the-ground-enemies-dont-stop-spawning-theres-no-ulfrictullius)
- [Technical](#technical)
  - [I'm randomly crashing!](#im-randomly-crashing)
  - [My performance is really terrible, low FPS, input lag during combat!](#my-performance-is-really-terrible-low-fps-input-lag-during-combat)
  - [I have a bug that's not in this list.](#i-have-a-bug-thats-not-in-this-list)
  - [The "scenes" take forever to start, and sometimes don't start at all.](#the-scenes-take-forever-to-start-and-sometimes-dont-start-at-all)
  - [The "scenes" are misaligned! Tab As are not going into Slot Bs!](#the-scenes-are-misaligned-tab-as-are-not-going-into-slot-bs)
  - [I enabled a feature and it's not working.](#i-enabled-a-feature-and-its-not-working)
  - [I added a mod and something weird happened.](#i-added-a-mod-and-something-weird-happened)
  - [There's more than 255 ESPs! Will this thing even launch?](#theres-more-than-255-esps-will-this-thing-even-launch)
  - [My load order got fucked up!](#my-load-order-got-fucked-up)
  - [Why do I have to CTRL-CLICK to build _BodySlide_?](#why-do-i-have-to-ctrl-click-to-build-bodyslide)
  - [My body looks boring and flat! or My boobs are melting into the ground!](#my-body-looks-boring-and-flat-or-my-boobs-are-melting-into-the-ground)
  - [I read a skill book but my skill didn't go up!](#i-read-a-skill-book-but-my-skill-didnt-go-up)
  - [What the hell! I'm moving backwards! I can't go into first person! I teleported under the ground! **or** I shrunk to a centimeter in height!](#what-the-hell-im-moving-backwards-i-cant-go-into-first-person-i-teleported-under-the-ground-or-i-shrunk-to-a-centimeter-in-height)
  - [One of my prostitution quests glitched out!](#one-of-my-prostitution-quests-glitched-out)
  - [Hey! I'm not supposed to respawn outside of the Clockwork or Project AHO mods!](#hey-im-not-supposed-to-respawn-outside-of-the-clockwork-or-project-aho-mods)
  - [I crash in Project AHO when I complete a certain quest!](#i-crash-in-project-aho-when-i-complete-a-certain-quest)

## Updates

### An update came out! It's new and shiny! What should I do?

**DO NOT UPDATE if you wish to continue your game.**

First, check CHANGELOG.md. If you are not interested in the changes, or they do not address a bug you are having, **do not update**.

**To confirm: all BodySlide customizations, and additional mods you have installed on top of the Modlist will be deleted. Your saves and downloads folders will not be touched!**

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite_ button.

## Content

### What gives? I want creatures! Where is Cursed Loot? Where is the roleplay? This is too softcore!

Boy did you ever download the wrong list. This list is mostly for playing Skyrim with titties in it.

Your only option at present is to install the _Dungeons & Deviousness_ modlist to experience the most Lover's Lab content this side of an Oldrim installation. You may feel that _DND_ goes too hard in the direction of suffering and roleplay. If this the case, consider reading about the mods inside it and configuring the menus more to your liking. They are actually very customizable.

## Gameplay

### What the fuck? Mirabelle, the College of Winterhold tour guide, is wandering all over the damn place!

Yeah, Skyrim Sewers expands the Midden and kinda fucks up her pathing, from what I understand. You can just go straight to the main hall where Tolfdir is and skip her little spiel. If for some reason you wish to hear it, I recommend opening console and typing "save funclist 1". A text document will pop up. Search in there for **second** occurrence of "Mirabelle Ervine". You should get a number at the far left like "0001C1B9". Every time she disappears on you, just open console and type "player.moveto 0001C1B9" (replace with your code, it will be different). 

### What the fuck? The Civil War questline is horribly fucked up. I can't complete the Battle(s) of Whiterun / Solitude / Windhelm. People are inverting backwards off the ground. Enemies don't stop spawning. There's no Ulfric/Tullius!

The Civil War questline is incredibly broken even in vanilla Skyrim partially due to the large actor count and infinitely spawning enemies. Pile on CGO scripting all attack patterns and animations and Ultimate Dodge scripting all movement and you have a recipe for disaster. Even if you do manage to complete it, countless other quests will be broken due to destroyed buildings / dead NPCs / flagged variables. It's recommended that you complete this questchain near the very end of your playthrough, if at all. If you choose to do so, I recommend keeping the following things in mind:

1. Before you do _any_ of these big battles with infinite spawns, _disable SexLab Aroused in the MCM!_ **IMPORTANT** You can turn it back on afterward.
2. Infinite enemy spawns are based around the destructible barricades. Hit them three times with a weapon or Destruction spell to destroy them and stop spawns in that area.
3. The above does not always work. If you find enemies never stop spawning, _sprint_ to the capitol building of the city you are attempting to reclaim (Dragonsreach, Castle Dour, etc) and make your way inside.
4. The conclusion of the Battle for Whiterun / Solitude / Windhelm is triggered by entering this capitol building.
5. You do not need to escort Ulfric, Galmar, Tullius, Likke or anyone else all the way to the capitol building. Sometimes they won't even spawn when you enter the city! Merely entering it yourself is enough. Just as followers appear beside you, so will the faction leaders.
6. Enjoy the rest of your horribly broken playthrough.

## Technical

### I'm randomly crashing!

You probably don't have enough paged RAM. Skyrim is very badly optimized. Try increasing your pagefile size. The recommendation is to set it to "System Managed" for all of your hard drives, but you can read specific instructions by going to any Wabbajack Discord channel and typing ``!pagefile`` 

### My performance is really terrible, low FPS, input lag during combat!

Your CPU or GPU are probably too weak. Head over to my Discord server and check the pins. There are many tips for improving performance on lower-end machines, and they can be used with practically any Wabbajack modlist!

### I have a bug that's not in this list.

The best way to get it looked at is to submit it to [Issues](https://github.com/cacophony-wj/LeS/issues). It's a list, I remember lists, I don't remember or sometimes even notice other things.

If you don't want to do that, I'm not going to be particularly strict about this since people have many reasons to avoid creating yet another account somewhere. So just drop by Discord. If I see it and it's not a known issue I'll try to help.

### The "scenes" take forever to start, and sometimes don't start at all.

SexLab is far from perfect. If you encounter this problem, try cycling the console or pause menus every couple seconds until the scene begins.

### The "scenes" are misaligned! Tab As are not going into Slot Bs!

SexLab is far from perfect. Use the hotkeys to align the scene. L goes closer, Shift-L farther away. ; goes higher, : goes lower. ' moves to the left, " to the right. Check the hotkeys menu in the _SexLab_ MCM for more commands.

### I enabled a feature and it's not working.

I won't answer questions about features I disabled. I disabled them because I couldn't get them to work.

### I added a mod and something weird happened.

Long and the short of it is, you're on your own unless I'm in a good mood.

### There's more than 255 ESPs! Will this thing even launch?

Yes. ESPs flagged as ESL don't count. Double click the little number to see how many real ESPs there are. Answer: a shockingly low amount!

### My load order got fucked up!

I have included backups. Click the swirly arrows. There's one for the load order (right pane) and one for the install order (left pane). Be sure to get the most recent one!

### Why do I have to CTRL-CLICK to build _BodySlide_?

_Mod Organizer 2_ does not put edits to existing files in the _overwrite_ folder, only newly created files. _CBBE_, _3BBB_ and _BD_ come with "default" meshes that will be changed by _BodySlide_ if you do not direct them to the proper directory yourself. Likewise, _Nemesis_ edits all the animation source files when it updates instead of putting the changes in the overwrite folder. If you don't believe me, I encourage you to check _MO2_'s documentation or the _Nemesis_ closed _Issues_ section on Github. If this doesn't convince you, I encourage you to test it yourself.

### My body looks boring and flat! or My boobs are melting into the ground!

You either didn't run _BodySlide_ or ran it wrong. Follow all the steps in the [Female Bodies and Outfits](https://github.com/cacophony/LeS/blob/master/BODYSLIDE.md) section again, especially the bits about making sure everything went to the correct directory.

### I read a skill book but my skill didn't go up!

This is because you "can't concentrate" if you're horny, so you don't get 100% skill experience from skill books. Check the _Magic Effects_ tab of your _Magic_ window for **red** effects that affect experience gain. Usually they are marked **Lover's Desire**. Take care of business and _then_ read the book.

### What the hell! I'm moving backwards! I can't go into first person! I teleported under the ground! **or** I shrunk to a centimeter in height!

This appears to be a bug with _SexLab Utility Plus_ which is still kinda ironing things out. The only thing you can do is reload, and if that doesn't work, exit Skyrim, launch it, and then reload.

### One of my prostitution quests glitched out!

The mod in question, _Radiant Prostitution_, was rather, shall we say, inexpertly put together and subsequently abandoned before it could be polished up. Before you accept one of the higher-level quests (something more than just walking around looking for Johns), be certain to back out and save your game. After accepting the quest, watch for error messages in the upper-left corner of the screen and consider reloading if you get one such as "Target location does not belong to a faction."  Bear in mind, if you receive a quest for a location that has not been enabled, such as a military camp before the Civil War begins, you will not be able to locate your target location. You will need to reload.

If you receive no such messages, save again, then go to the location of your quest. If the location is locked, consider reloading from _before you accepted the quest_ as that particular quest is probably bugged. Ensure that you can complete the quest and receive kudos from your client(s). If this does not happen, consider reloading. Assuming all does manage to complete, return to the innkeeper for your payment. 

If anything goes wrong throughout these quests, you will have to reload from before accepting it, so as to receive a different randomly-generated one. To be quite honest, very little about this mod works well aside from simple brothel or street walking.

### Hey! I'm not supposed to respawn outside of the Clockwork or Project AHO mods!

This is true. If you die in these mods and respawn with Ashes, you game may be permanently messed up. I recommend disabling _Ashes_ before doing either of these quest chains. Or, if you die, simply ensure that you reload instead of continuing.

### I crash in Project AHO when I complete a certain quest!

Try this. Load before you start the quest's conclusion. Complete a step. Save. Reload. Complete the next step. Continue until you finish the quest without crashing. I have confirmation that this does work.
