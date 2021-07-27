- [DODGE ISN'T WORKING! or I CAN'T SNEAK!](#dodge-isnt-working-or-i-cant-sneak)
- [Content](#content)
  - [What gives? I want creatures! Where is Cursed Loot? Where is the roleplay? This is too softcore!](#what-gives-i-want-creatures-where-is-cursed-loot-where-is-the-roleplay-this-is-too-softcore)
- [Gameplay](#gameplay)
  - [I don't have one of those ancient ass NUMPADs! How the hell am I gonna use OStim?](#i-dont-have-one-of-those-ancient-ass-numpads-how-the-hell-am-i-gonna-use-ostim)
  - [My follower is walking around with an exploded head! (Or other types of gore.)](#my-follower-is-walking-around-with-an-exploded-head-or-other-types-of-gore)
  - [The Civil War questline is horribly fucked up. I can't complete the Battle(s) of Whiterun / Solitude / Windhelm. People are inverting backwards off the ground. Enemies don't stop spawning. There's no Ulfric/Tullius!](#the-civil-war-questline-is-horribly-fucked-up-i-cant-complete-the-battles-of-whiterun--solitude--windhelm-people-are-inverting-backwards-off-the-ground-enemies-dont-stop-spawning-theres-no-ulfrictullius)
- [Technical](#technical)
  - [I'm randomly crashing!](#im-randomly-crashing)
  - [As soon as I start the game in the main "overworld" everybody starts spinning around and collapsing at the speed of light!](#as-soon-as-i-start-the-game-in-the-main-overworld-everybody-starts-spinning-around-and-collapsing-at-the-speed-of-light)
  - [I have problems with the camera! Flickering, weird 1st person body clipping! Can't switch to 3rd person!](#i-have-problems-with-the-camera-flickering-weird-1st-person-body-clipping-cant-switch-to-3rd-person)
  - [My performance is really terrible, low FPS, input lag during combat!](#my-performance-is-really-terrible-low-fps-input-lag-during-combat)
  - [I have a bug that's not in this list.](#i-have-a-bug-thats-not-in-this-list)
  - [I added a mod and something weird happened.](#i-added-a-mod-and-something-weird-happened)
  - [There's more than 255 ESPs! Will this thing even launch?](#theres-more-than-255-esps-will-this-thing-even-launch)
  - [My load order got fucked up!](#my-load-order-got-fucked-up)
  - [I crash in Project AHO when I complete a certain quest!](#i-crash-in-project-aho-when-i-complete-a-certain-quest)
  - [I can't take two steps in Lucien's final dungeon without freezing or crashing!](#i-cant-take-two-steps-in-luciens-final-dungeon-without-freezing-or-crashing)
- [For More Information](#for-more-information)


## DODGE ISN'T WORKING! or I CAN'T SNEAK!

I see you are not the type of person to read readmes. It's addressed at the end of the MCM document, but for dodge and sneak to work properly you must press the G key twice. If I knew a way to make this unnecessary, I would. Please look at the relevant portions of the other documents for more information. And while you're there, try skimming over them all again to make sure you haven't missed something. 

## Content

### What gives? I want creatures! Where is Cursed Loot? Where is the roleplay? This is too softcore!

Boy did you ever download the wrong list. This list is mostly for playing Skyrim with titties in it.

Your only option at present is to install the _Dungeons & Deviousness_ modlist to experience the most Lover's Lab content this side of an Oldrim installation. You may feel that _DND_ goes too hard in the direction of suffering and roleplay. If this the case, consider reading about the mods inside it and configuring the menus more to your liking. They are actually very customizable.

## Gameplay

### I don't have one of those ancient ass NUMPADs! How the hell am I gonna use OStim?

From my user _BigMac_

> If you hold F8 for 10 seconds it activates OSAs emergency rebind. Where Lshift pulls up the menu and WASD is how you nav. You can then rebind the keys manually. I use P L ; '  to nav, O and [ as yes/no and ] as toggle.

### My skills don't seem to be leveling up!

Sleep to learn new skills. You can pick whatever you want!

### My follower is walking around with an exploded head! (Or other types of gore.)

The fix I installed for this doesn't always trigger. Try casting the "Maximum Mending" spell you started the game with. It removes the gore effect from all nearby NPCs.

### The Civil War questline is horribly fucked up. I can't complete the Battle(s) of Whiterun / Solitude / Windhelm. People are inverting backwards off the ground. Enemies don't stop spawning. There's no Ulfric/Tullius!

The Civil War questline is incredibly broken even in vanilla Skyrim partially due to the large actor count and infinitely spawning enemies. Pile on CGO scripting all attack patterns and animations and Ultimate Dodge scripting all movement and you have a recipe for disaster. Even if you do manage to complete it, countless other quests will be broken due to destroyed buildings / dead NPCs / flagged variables. It's recommended that you complete this questchain near the very end of your playthrough, if at all. If you choose to do so, I recommend keeping the following things in mind:

1. Infinite enemy spawns are based around the destructible barricades. Hit them three times with a weapon or Destruction spell to destroy them and stop spawns in that area.
3. The above does not always work. If you find enemies never stop spawning, _sprint_ to the capitol building of the city you are attempting to reclaim (Dragonsreach, Castle Dour, etc) and make your way inside.
4. The conclusion of the Battle for Whiterun / Solitude / Windhelm is triggered by entering this capitol building.
5. You do not need to escort Ulfric, Galmar, Tullius, Likke or anyone else all the way to the capitol building. Sometimes they won't even spawn when you enter the city! Merely entering it yourself is enough. Just as followers appear beside you, so will the faction leaders.
6. Enjoy the rest of your horribly broken playthrough.

## Technical

### I'm randomly crashing!

You probably don't have enough paged RAM. Skyrim is very badly optimized. Try increasing your pagefile size. The recommendation is to set it to "System Managed" for all of your hard drives, but you can read specific instructions by going to any Wabbajack Discord channel and typing ``!pagefile`` 

### As soon as I start the game in the main "overworld" everybody starts spinning around and collapsing at the speed of light!

This happens sometimes to some people when the framerate is not capped. Please ensure you copied over the _Game Folder Files_ as the main readme suggests. While you're at it, why don't you skim it again to make certain you didn't miss anything? I know it's long, but it's kind of important.

### I have problems with the camera! Flickering, weird 1st person body clipping! Can't switch to 3rd person!

These are all caused by the extremely janky customization that makes first person POV sex under OStim a possibility. You are probably better off disabling both "Improved Camera" and the "Improved Camera INI" in the left pane of MO2. They do not have traditional ESPs, so your save will be fine. For a compromise, you can switch _to_ third person with the "F" key, and _back_ to first person with the scroll wheel. yes it is quite jank

### My performance is really terrible, low FPS, input lag during combat!

Your CPU or GPU are probably too weak. Head over to my Discord server and check the pins. I have a "Performance" version of _Licentia_ available there that greatly reduces the system requirements. You can get them even lower by switching the _ENB_ to "Serio" or removing it entirely! 

### I have a bug that's not in this list.

The best way to get it looked at is to submit it to [Issues](https://github.com/cacophony-wj/LeS/issues). It's a list, I remember lists, I don't remember or sometimes even notice other things.

If you don't want to do that, I'm not going to be particularly strict about this since people have many reasons to avoid creating yet another account somewhere. So just drop by Discord. If I see it and it's not a known issue I'll try to help.

### I added a mod and something weird happened.

Long and the short of it is, you're on your own unless I'm in a good mood.

### There's more than 255 ESPs! Will this thing even launch?

Yes. ESPs flagged as ESL don't count. Double click the little number to see how many real ESPs there are.

### My load order got fucked up!

I have included backups. Click the swirly arrows. There's one for the load order (right pane) and one for the install order (left pane). Be sure to get the most recent one!

### I crash in Project AHO when I complete a certain quest!

Try this. Load before you start the quest's conclusion. Complete a step. Save. Reload. Complete the next step. Continue until you finish the quest without crashing. I have confirmation that this does work.

### I can't take two steps in Lucien's final dungeon without freezing or crashing!

Lucien's final dungeon has a TON of custom models and assets that are quite demanding even WITHOUT the massive texture overhauls of _Licentia_. I have already installed the only mod created to resolve this issue by adding more occlusion planes to hide non-visible objects. My recommendation to you is to either disable all 4K Texture mods temporarily (except those with ESPs -- look inside the mod folder) and also disable the _SmoothCam_ mod. Hopefully this fixes your problem, otherwise, I'm afraid I don't know what to do as these freezes seem related to weird system configurations. My team members were able to push through the dungeon even with the crashes by carefully staring at the ground and using _Whirlwind Sprint_ in the worst areas, but they are _extremely_ determined!

## For More Information

So you've had a taste of the caco experience and want more, you say? To get specific help with this modlist or modding in general (NSFW or SFW) take your happy ass to my discord server located at the link below. Depending on the phases of the moon you may find alphas of lists in progress, betas of lists being tested, tips for lewding lists and games yourself, or other strange projects. I'm also one of the few WJ modders who welcome additions to his list (or any list) and offer my services as support. While you're there drop in the "co-operating" channel to discuss Dark Souls and other co-op games, or the "hard topics" channel for those spicy subjects that'll get you banned everywhere else! Enjoy!

https://discord.gg/VVRWPJmgf7
