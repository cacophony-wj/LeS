- [Updates](#updates)
  - [An update came out! It's new and shiny! What should I do?](#an-update-came-out-its-new-and-shiny-what-should-i-do)
- [Technical](#technical)
  - [I have a bug that's not in this list.](#i-have-a-bug-thats-not-in-this-list)
  - [I enabled a feature and it's not working.](#i-enabled-a-feature-and-its-not-working)
  - [I added a mod and something weird happened.](#i-added-a-mod-and-something-weird-happened)
  - [There's more than 255 ESPs! Will this thing even launch?](#theres-more-than-255-esps-will-this-thing-even-launch)
  - [Why do I have to CTRL-CLICK to build _BodySlide_?](#why-do-i-have-to-ctrl-click-to-build-bodyslide)
  - [My body looks boring and flat! or My boobs are melting into the ground!](#my-body-looks-boring-and-flat-or-my-boobs-are-melting-into-the-ground)
  - [I read a skill book but my skill didn't go up!](#i-read-a-skill-book-but-my-skill-didnt-go-up)
  - [It seems like I'm about to have sex but nothing is happening. Everyone is just standing around making breathing or grunting noises.](#it-seems-like-im-about-to-have-sex-but-nothing-is-happening-everyone-is-just-standing-around-making-breathing-or-grunting-noises)

## Updates

### An update came out! It's new and shiny! What should I do?

**DO NOT UPDATE if you wish to continue your game.**

First, check CHANGELOG.md. If you are not interested in the changes, or they do not address a bug you are having, **do not update**.

If you do update, copy out the entire _profiles_ folder within the _LeS_ directory to somewhere **you will remember.**

**This is your final warning, Wabbajack will delete your saves when updating!**

**To confirm: all saves, BodySlide customizations, and additional mods you have installed on top of the Modlist will be deleted. Your downloads folder will not be touched!**

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite_ button.

When the update is complete, **move** the _profiles_ folder back into the _Licentia et Servitium_ folder and choose **not** to overwrite. (Your saves will be restored but any modlist changes will be kept.)

Next **delete** the _profiles_ folder leftovers from your backup, as they only have old and useless files.

You should be ready to continue as per the installation instructions in the README (back on your browser)

## Technical

### I have a bug that's not in this list.

Submit it to [Issues](https://github.com/cacophony-wj/LeS/issues). You might not know about the issues tab until just now. You might not want to create an account. You will probably want to talk about it on Discord. I might respond to you, I might not. I might tell you to submit it, I might just ignore you. If you're serious about me looking at a bug submit it. I'll at least give you a response.

### I enabled a feature and it's not working.

I won't answer questions about features I disabled. I disabled them because I couldn't get them to work. If you did, that's great, explain how and I'll pin it with a note to ping you so you can support people who ask questions about it.

### I added a mod and something weird happened.

See the main README. Long and the short of it is, you're on your own unless I'm in a good mood.

### There's more than 255 ESPs! Will this thing even launch?

Yes. ESPs flagged as ESL don't count. Double click the little number to see how many real ESPs there are. Answer: a shockingly low amount!

### Why do I have to CTRL-CLICK to build _BodySlide_?

_Mod Organizer 2_ does not put edits to existing files in the _overwrite_ folder, only newly created files. _CBBE_, _3BBB_ and _BD_ come with "default" meshes that will be changed by _BodySlide_ if you do not direct them to the proper directory yourself. Likewise, _Nemesis_ edits all the animation source files when it updates instead of putting the changes in the overwrite folder. If you don't believe me, I encourage you to check _MO2_'s documentation or the _Nemesis_ closed _Issues_ section on Github. If this doesn't convince you, I encourage you to test it yourself.

### My body looks boring and flat! or My boobs are melting into the ground!

You either didn't run _BodySlide_ or ran it wrong. Follow all the steps in the [Female Bodies and Outfits](https://github.com/cacophony/LeS/blob/master/BODYSLIDE.md) section again, especially the bits about making sure everything went to the correct directory.

### I read a skill book but my skill didn't go up!

This is because you "can't concentrate" if you're horny, so you don't get 100% skill experience from skill books. Check the _Magic Effects_ tab of your _Magic_ window for **red** effects that affect experience gain. Usually they are marked **Lover's Desire**. If you're not locked up with something, alleviate that need and then read the book. If you're locked into gear and can't take care of business, you'll have to weigh the benefit of reduced experience or leaving the book behind until you find another copy of it.

###  It seems like I'm about to have sex but nothing is happening. Everyone is just standing around making breathing or grunting noises.

_Skyrim Special Edition_ is not well supported yet by the _Lover's Lab_ community, or at least not as robustly. Most players seeking to use such content do so on _Oldrim_ or _Legendary Edition,_ which unfortunately suffers from an inferior engine as far as stability and memory management goes. _Legendary Edition_ is also not "officially" available on _Steam_ any longer, which discourages mainstream mod (and modlist) authors from supporting it. 

As such, animations triggered from the SE versions of _Defeat_ and _Cursed Loot_ seem to be called in a slightly different fashion than those from _SL Tools_, _SL Solutions_, or _SLEN_. They suffer from intolerable script lag at times, regardless of how many mods or animations are installed. I understand it's a known issue that is being worked on, but until it is resolved, you'll have to break your immersion a bit. If an animation seems stuck, open the console with the tilde key (`), wait for all messages to cycle, then close the console again. You may have to repeat this process a couple of times. If nothing you do gets an animation to start, post about in [Issues](https://github.com/cacophony-wj/LeS/issues).
