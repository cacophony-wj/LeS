![Licentia logo](images/LicentiaCompile3.png "Licentia")

_Thank you to Lance for the above image._

- [ATTENTION! THE LATEST VERSION OF SKYRIM, YES, THE $20 UPGRADE EVERYONE IS COMPLAINING ABOUT, IS NOW REQUIRED TO INSTALL LICENTIA.](#attention-the-latest-version-of-skyrim-yes-the-20-upgrade-everyone-is-complaining-about-is-now-required-to-install-licentia)
- [Preamble](#preamble)
  - [FEATURING ARTIFACTS OF SKYRIM REVISED, UNIVERSAL STORAGE AND STAFF ENCHANTING!](#featuring-artifacts-of-skyrim-revised-universal-storage-and-staff-enchanting)
  - [STRONG WARNINGS](#strong-warnings)
    - [DO NOT ALTER THE MODLIST AND REQUEST SUPPORT FROM WABBAJACK STAFF!](#do-not-alter-the-modlist-and-request-support-from-wabbajack-staff)
  - [Requirements](#requirements)
    - [System Specs](#system-specs)
  - [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Config](#steam-config)
   - [Using Wabbajack](#using-wabbajack)
  - [Downloading and Installing](#downloading-and-installing)
  - [Problems with Wabbajack](#problems-with-wabbajack)
  - [Post-Installation](#post-installation)
  - [Preparing Your Page File](#preparing-your-page-file)
  - [Preparing the Game](#preparing-the-game)
  - [Launching the Game](#launching-the-game)
- [PLEASE CLICK THE BELOW LINK TO CONTINUE THIS ESSENTIAL README. THEN RETURN HERE TO COMPLETE THIS ESSENTIAL README.](#please-click-the-below-link-to-continue-this-essential-readme-then-return-here-to-complete-this-essential-readme)
  - [Updating the Modlist](#updating-the-modlist)
  - [Removing the Modlist](#removing-the-modlist)
  - [Contact](#contact)
  - [Contributing](#contributing)
  - [Changelog](#changelog)

### Interested in other NSFW lists? Join my Discord Server!

There you can find _Tsukiro,_ low-key a much more professional list than _Licentia_ and featuring far more slooty outfits, degenerate content, and a unique parry-and-riposte form of combat that will have you coming back for more! Or chill out with Camilla Valerius in cyberspace with _Tahrovin_, a list for _Skyrim VR_ that allows you to pick up Nazeem with your hands and throw him across the Whiterun market if you want! 

Also in development there: _Devil's Food Cake Reborn,_ an NSFW list for _Fallout 4_ that will feature a full replacement of all those boring pipe guns with modern weapons, as well as more outfits and dressup gear than you can shake a stick at! Finally, if you fancy building a degen list of your own but don't want the boring step of installing dozens of fixes and tools, grab _Skyrim Modding Essentials - Fixes & Tools: But Sexy!_ a version of Luca's Essentials list that has the bare minimum _Ostim_ configuration right on top! 

You can find the link to my Discord server at the end of this document.

# ATTENTION! THE LATEST VERSION OF SKYRIM, YES, THE $20 UPGRADE EVERYONE IS COMPLAINING ABOUT, IS NOW REQUIRED TO INSTALL LICENTIA.

I realize this will be an unpopular decision, but let me explain. I like this content. I bought it when it was full price. I bought it again as an _Anniversary Edition._ The reasons? 

I have 3,000 hours playing this game and maybe 6,000 modding it. It has by far been the number one most value for the money of any game in my entire life. Todd deserves any amount of money he chooses to ask for.

Also, the game only exists in such a moddable form because Todd wants it to. The only way it will continue to be this way is if mods continue to make Todd money. Buying all this content is my way of voting for Starfield and TES6 to be just as customizable as Skyrim is.

Lastly? I bought all this stuff, so I damn well want to play it. Keeping a non-upgraded version for people who prefer not to pay for it is extra work that I will never benefit from. On top of all that, the extra content makes heavy edits to the world, so when I remove it, I need to regenerate distant terrain. This is an additional 3 - 6 hours of work depending on how error-prone the process is. And it would need to be done twice, once for the added content, once without, every time I update the list. 

No offense, but you saving $20 one time does not matter much to me if it means an extra six hours of work every week.

This will never change. Complaining about it will get you nowhere. If you want to take a stand against Todd's extra 20, do so with another list.

Now that that's out of the way, how do you ensure that you have the proper version of Skyrim, with all Creation Club Content required to install the list? Refer to the Pre-Installation steps later in this document.

# Preamble

**This Modlist contains mods with sexual content and you need to be of legal age in your country (most western countries: 18+, some eastern ones: 21+)**.

Welcome to the latest incarnation of _Licentia_. This modlist is intended as a high fantasy "Game of Thrones" Skyrim -- ultimate power fantasy where you can use an incredible amount of perks and spells to make the hero _you_ want, with just a touch of racy sexuality. However, it _does not_ do so via unimmersive "slooty" outfits such as bikini armors, lingerie, or various getups that look like costumes or pajamas. It also does not make the sex the point of the game -- you are not simulating sexual slavery with granular breast inflation values down to the millimeter or getting assaulted against your will by everything with a pulse -- the sex is meant is a side minigame or "break" between your hard but rewarding life as an adventurer.

**I apologize for any oversights or inconsistencies in this readme.** It has had many additions and removals over the years and likely needs a full rewrite soon. Until I perfect this document, please struggle through as best you can and feel free to ask me for assistance on Discord or via this Github.

_Want more detailed information before committing to a 300+ GB download?_ Check out the links below.

[Showcase and Review Video by "Official" Wabbajack Streamer _DroppedIceCream_](https://www.youtube.com/watch?v=vM0xFFFirRc)

[Showcase and Gameplay Video by YouTube Personality _Deep Voice_](https://www.youtube.com/watch?v=W8AsI1o1-z4)

[Various Screenshot Galleries of _Licentia_ (Click on the "Grab Licentia" Link)](https://cacophony.me)

[Positive Review of Licentia on Reddit](https://www.reddit.com/r/skyrimmods/comments/qcvrc6/licentia_review_with_links_and_a_thank_you_to_mod/)

[List of All Mods in Licentia on Load Order Library](https://loadorderlibrary.com/lists/licentia)

_Came here because you are experiencing a bug? Check out the Troubleshooting Document:_

[Licentia Troubleshooting](https://github.com/cacophony-wj/LeS/blob/master/TROUBLESHOOTING.md)

The first thing you should probably know is that I am more of a fan of old-school RPG mechanics. I don't like grinding out daggers to level up Smithing or wandering in circles next to a sleeping person to level up Stealth. Therefore, your level does not increase with your skills. Instead, it is the other way around. As you kill things and complete quests, "Experience Points" accumulate until you gain a "level" at which point you can sleep for at least 1 hour in any bed and distribute them to any skill you wish. Also, there are hundreds of additional perks in this modlist, to encourage you to experience a wide variety of options. Therefore, you get more perks than normal. There are also options to convert souls and quests into perks, as well as tradable ones from the mod VIGILANT. Plenty enough to develop any build and become near god-like, but not quite so much that you do everything with one character.

A note about difficulty. _CGO, AGO, Vokriinator Black,_ and all the camera, movement, and spell mods I have included mutiply the player's power almost exponentially. I have yet to stumble on a solution for game balance that accomodates most play styles. As it is, with the MCMs I have scripted, it is probably too easy for anyone who knows the ins and outs of the game. For now, I recommend you leave the values at default until you get a follower (or two) and maybe reach level 10. Then up them as things get too easy (this is a problem with vanilla as well). Not only can you change the difficulty in _Settings,_ you can mess with the options in _Deadly Dragons_ and _Wildcat_ to make things pretty tough on yourself. Dragons will one shot you if their mod is set to "Insane," _Wildcat_ will have you flipping your keyboard when you get juggled with "Full Body Stagger." Experiment! I'll get something better in there one day. I am really bad at the game, lack quality reflexes, and never get a chance to progress very far before something updates or breaks. Report your findings! I may not like to hear them at first but I am always gratified in the end.

A note about the signature followers _Auri, Inigo_ and _Kaiden._ These guys are badasses in the Vanilla game but are stone-cold killers in _Licentia._ I have user reports of them doing 7,000 - 10,000 damage per hit after all the perks given to them are converted to their _Vokriinator Black_ equivalents. As a result, they have all been severely nerfed to put more focus on the player. Most perks having to do with offense and damage multiplication have been removed, a few of the defensive ones are left so they can serve as tanks or distractions. Please keep this in mind as you play and do not report this to the innocent mod authors who designed these mods, they are _not_ meeting their original intention in this list and never could. It is not their problem. _Lucien_ has been left untouched as he has only very basic dual-casting perks at the start. However, he grows as you travel with him, so he may end up quite the badass himself!

A note about "save scumming," which is the practice of quickly saving and reloading many times in a row to get a perfect result, the "Edge of Tomorrow" method of playing a videogame. If you spend 30 minutes reloading after death again and again, especially during or after combat, a _lot_ of stuff will break on your save. I have experienced this first-hand. If you can't get past a group of enemies without repeated deaths and reloads, consider accepting your limitations and retreating, or loading an hour or so back and dialing the difficulty down a few notches. If you continue to save and load rapidly, complete corruption of your save can result. This includes symptoms such as being unable to wield weapons, die, or even load the game. 

# FEATURING ARTIFACTS OF SKYRIM REVISED, UNIVERSAL STORAGE AND STAFF ENCHANTING!

Go [here](MODGUIDE.md) for credits and descriptions of the major mods in _Licentia_.

# STRONG WARNINGS

Before asking a question, look at [Troubleshooting](https://github.com/cacophony-wj/LeS/blob/master/TROUBLESHOOTING.md). Many common questions are answered there.

## Requirements

- [Nexus Premium Account](https://forums.nexusmods.com/index.php?/store/category/1-premium-membership/)
- [LoversLab Account](https://www.loverslab.com/)

### System Specs

My best estimate as to what you need to play _Licentia_ enjoyably is as follows:

- CPU: >= 8th gen Intel, OR >= AMD Ryzen 5000 series
- GPU: >= NVIDIA RTX 2070, OR >= AMD RX 5700; please keep in mind that AMD cards tend to have problems with ENB and are not recommended
- RAM: >= DDR4 with at least 16GBs

Please bear in mind that this is an extremely demanding list. Even with very high system specs you may experience slowdowns and stutter periods as various resources load in. I have a 3090 and it happens to me sometimes when several outdoor cells at once spawn their mobs. As a matter of fact, there are individual files within this list that are over 4GB in size and require a fast, reliable Internet connection merely to install successfully. 

If you have any doubts about your ability to install the modlist or prefer a responsive, lightweight list with an emphasis on performance and a far more simple install process, why not try out the successful Nexus Collection called "Immersive & Adult." It features many of the same mods and features and performs far better on low- and midrange hardware. Join the Discord and say hello to my friend Canliberk while you are there.

- [Immersive & Adult on Nexus Next](https://next.nexusmods.com/skyrimspecialedition/collections/xxsqm4)

Also of UTMOST IMPORTANCE is that you have a VERY LARGE PAGEFILE on the fastest hard drives available to you. I networked with Wabbajack staff to drastically improve the texture quality in this list -- Wabbajack's recommendation of a 20GB pagefile is not enough because that size crashed me in testing. I myself have it at 40GB, but you could probably get away with "System Managed" on each of your SSD's (the OS drive and at least one more)

Speaking of which, everything should be installed on an SSD that has at least 250GB of space available. The game is unplayable on an HDD, although you can relocate your downloads folder to one if you need space.

Please note that you will also require _at least_ an additional 30GB on the drive you installed Wabbajack.exe to for extraction and recompression of files.

## Installation

##  Pre-Installation

These steps are only needed if you install this Modlist for the first time. If you update the Modlist, jump straight to **Updating**  in the **Troubleshooting** section.

###  Installing Microsoft Visual C++ Redistributable Package

I doubt you need to do this since you likely already have this installed. The package is required for MO2 and you can download it from Microsoft. Download the x64 version under "Visual Studio 2015, 2017 and 2019". <a href="https://aka.ms/vs/16/release/vc_redist.x64.exe">Direct link</a> if you can't find it.

### Installing the latest DOT.NET Redistributable

[You can get it here](https://dotnet.microsoft.com/en-us/download/dotnet/5.0/runtime)

Install both `CONSOLE-APPS-x64` and `DESKTOP-APPS-x64`

###  Steam Config

**Change Steam's Update Behavior**

SSE is still being updated by Bethesda (they only add Creation Club content). Whenever the game updates, the entire modding community goes silent for the next one or two weeks because some mods need to be updated to the latest game runtime version.

To ensure that Steam does not automatically update the game for you and lock you out of playing your _Wabbajack_ modlist(s), head over to the Properties window, navigate to the Updates tab and change Automatic updates to _Only update this game when I launch it_. You should also disable the _Steam Cloud_ while you're at it.

**Set the Game language to English**

Wabbajack will check your game files and make sure that we have the same version. This also means that any other language than English will fail the installation.

Open the Steam Properties window, navigate to the Language tab and select English from the dropdown menu.

**Install Skyrim** 

Here is a step-by-step breakdown.

1. First purchase the _Skyrim Anniversary Edition_ Upgrade from Steam. It retails for about $20.00 USD (varies between territories.) There is no way around this. I will not make a version specifically for you, so do not ask. All complaints about this will be ignored.
2. Install the game via Steam using the typical process.
3. If you are already confident you have the _Anniversary Edition_ of Skyrim, please do the following steps anyway. I wish to make certain, because _this is the most common question asked in my support channels._
4. To verify your version of Skyrim, first ensure that your game is set to English. No other version of Skyrim will work. There are no exceptions.
5. In your Steam Library, right-click on the menu entry for Skyrim, select "Properties" and then select "Local Files." Click "Verify Integrity of Game Files" and wait.
6. You may receive an error that files need to be downloaded again. Wait for this process to complete.
7. If not, Steam will tell you that all files have been successfully validated. You are ready to continue ONLY if you receive this message. If you did not, repeat the above steps.
8. Next launch the game once from Steam. You may receive a prompt that your settings were detected or not detected. You may not. It does not matter, nor do any options you select here. Simply open the launcher, click through any messages, and launch the game from the launcher.
9. As soon as the intro logos finish displaying and the Skyrim logo appears, you should receive a prompt to "Download All Content?" Accept this option.
10. If you did not receive a prompt to download, select the _Creation Club_ option from the menu, and you should find a "Download All" prompt in there somewhere. If this message does not appear, you have not purchased the $20 Upgrade. Begin again from step 1.
11. Wait for the download process to complete. It takes about 20 - 30 minutes. You cannot Alt-Tab out of this process, you must wait.
12. You are now ready to continue.

**Disable or Uninstall Offensive Anti-Malware Programs**

It is recommended that you **exclude** three directories completely from any antivirus or anti-malware programs you may have on your system. These include the folder that _Wabbajack_ is installed to, the _Steam_ folder that _Skyrim Special Edition_ is installed to, **as well as** all directories in which you wish to install a list. _Please note that certain AV programs_ (_Bitdefender_ and _Webroot_ being the primary examples) _**do not completely exclude a folder or disable themselves when told to do so.**_ When in doubt, _rely only on Windows Defender_ for your anti-malware solution. It is free, 95% as effective as any other similar package you might find (the best AV has only a 40% detection rate), and if you are regularly visiting websites where malware is a risk, you are likely compromised anyway.

##  Using Wabbajack

##  Downloading and Installing

Due to continuing problems with the Lover's Lab API, several of the files must be downloaded manually. Duriing the installation process, you may be presented with various webpages from that, accomanied by instructions to download a specific file. Please click the green Download link and, if the file does not download, click again on the file name specified in the prompt. Refer to the status bar of the window for download progress, and wait for 100% before continuing. Please note that the automatic login available from Wabbajack's settings may not function correctly: you may need to log out via the GEAR ICON in the upper right, and log again normally using Lover's Lab's homepage (top left).

If for some reason something goes wrong, you can cancel the installation and download these files manually. The process will pick up from where it left off when you restart the install. There are only five files required from Lover's Lab, and to use them, place them in the same directory you specified for "Download Location" just above. Please download the _exact versions_ of all of the below files

- Version 2.7.9 of [Nether's Follower Framework](https://www.loverslab.com/files/file/6188-nethers-follower-framework/)
- Version Beta 5 of [OStim Solutions](https://www.loverslab.com/files/file/17441-ostim-solutions-a-sexlab-solutions-revisited-port/)
- Version 2.1 of [OTrainers](https://www.loverslab.com/files/file/18438-otrainers-ostim-trainers-with-benefits/)
- Only available version of [Schlongs of Skyrim Light SE](https://www.loverslab.com/files/file/3705-schlongs-of-skyrim-light-se/)

Often Google and MEGA files will frequently experience bandwidth caps. When this happens those files will also fail. You can download them manually via these links:

- [Artifacts_Revised 1.2.1 - Textures.7z](https://mega.nz/file/QWYBTaYY#6NTFsD3G_jtuHWGeTAQWcA1Rioch3D2KFhQobMD1Kpk)
- [SexLab Solutions Revisited 1.1.5 Voice Files.zip](https://mega.nz/file/j64AnQLQ#SsGVP7pBSv-P3FGO7TyryPHUTmZtT0fybF8fAJfVi8w)
- [Pubic Hair Overlays SE.zip](https://drive.google.com/file/d/1_sYhna-VKSKFOG8mNA8dWpByvNba42ZG)
- [Improved_Camera-1.0_Beta4.7z](https://drive.google.com/file/d/12hqOZbfeFK0zXJxpzsEXsyQyDclDQaZk)

After you have downloaded **EVERY ONE OF THESE FILES MANUALLY,** launch Wabbajack again, keep the settings the same as before, check "Overwrite," and press the **PLAY** button.

There are also several large files stored on Wabbajack's own servers, and since these are protected by CloudFlare, many ISPs are not configured to route them properly. Keep this in mind if you cannot finish the install because files with "Licentia" in the filename keep failing.

First try enabling the "Network Workaround" in Wabbajack's settings menu (gear icon, top right) and restart the process.

If that doesn't work, you will need a VPN set to the United States. (There are many high quality free, but slow, VPNs which have very good privacy policies. I am personally a fan of Proton because it's in Switzerland, with the same maniacal attention to security as the numbered bank accounts from the same place. . . . But I'm not your Dad.) 

If this STILL doesn't work, you can download them from the MEGA link below, but you will cap at downloads before you are finished. You can try creating an account to get around it, using a VPN, paying actual money, or waiting 24 hours between attempts. I'm sorry, I don't know what else to do.

[Licentia Custom Files - MEGA Shared Directory](https://mega.nz/folder/RawGxSQC#18F3HuX5i5MvXzsMb6ARGg)

Finally there may be certain files from Nexus which freeze or corrupt during download, or simply never complete. For these files, I recommend using the Nexus Website settings to change your local server to one closer to your physical location and rerunning Wabbajack a handful of times. If that does not work, you can attempt to download any files you have trouble with manually using the links below:

https://github.com/wabbajack-tools/mod-lists/blob/master/reports/wj-featured/Licentia/status.md

This list is a complete accounting of every file required to install my list. Feel free to refer to it as needed.

    Wait for Wabbajack to finish

The download and installation process can take a very long time depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. 

    Adjust the Installation Location to a directory located on the root directory of one of your drives
    For example, this might be "C:\Licentia", "D:\Licentia", or "E:\Licentia"
    Ensure the Download Location is where you wish it to be, it defaults to a location within the directory just above
    Click the Go/Begin button

To have the highest amount of threads and thus the fastest speed, it is advised to have ALL of the folders (for `Wabbajack.exe`, the modlist folder, and the downloads folder) on an SSD. 

It is not _technically_ necessary to have anything on an SSD for an install procedure. You can keep downloads on an HDD if you are low on space, or hell, install the whole thing to an external to keep for all time as a vast repository of Wabbajack. If you install **ANY PART OF THIS LIST** on **ANYTHING BUT A FAST SOLID STATE DRIVE**, it is recommended that you **OPEN THE GEAR ICON** described above and set both "Disk" and "Download" threads **NO GREATER THAN ONE.** This will make the excruciatingly slow process as fast as it can be on such slow drives.

As of my last check, _Licentia_ requires about 260 GB for the modlist itself, and about 160GB for the downloads. You will also need an additional 30 GB available on the same drive as `Wabbajack.exe` to store temporary working files. There may also be a small amount required in your `AppData` folder for various hash and patch caches, totaling no more than 5 - 10GB. You can feel free to relocate, delete, or archive the downloads or any of these temporary files after you are finished installing, they are not required to play the list, but they may be needed if you ever choose to update. 

Playing the list _will not be pleasant on a hard drive_ however. You will experience ten minute load times regularly, and possible weird scenarios where every person collapses to the ground into themselves, spinning infinitely at the speed of light. That, or framerates will be a veritable slide show. This really isn't fixable due to the suboptimal 2011 code handling over 100GB of textures. Get an SSD, my main man.

##  Problems with Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

**DO NOT CONTACT MOD AUTHORS DIRECTLY.**

I, cacophony, fully accept any responsibility for difficulties with this list and any conflicts I introduce, so please do not question mod authors on the _Nexus_, _Lover's Lab_, _Vector Plexus_ or any other site about bugs that may result from this lists' use. Direct your questions to me, not the innocent mod authors who should never be expected to support a modlist setup.

**Various files beginning with "cc" and ending with "esl" or "esm" failed to download.**

You did not purchase the $20 upgrade to Skyrim. This is not negotiable. Return to the beginning of this document and do everything again from square one.

**Problems downloading files from Lover's Lab or the Wabbajack CDN**

Lover's Lab files are obvious. CDN files have the word _Licentia_ in the filename. Refer to [this section] in TROUBLESHOOTING.md

**Could not download x:**

If a mod updated and the old files got deleted, it is impossible to download them. In this case just wait till the modlist receives an update.

**x is not a whitelisted download:**

This can happen when update the modlist receives an update. Check if a new update to the modlist is available and wait if there is none.

**Wabbajack could not find my game folder:**

Wabbajack will not work with a pirated version of the game. If you own the game on Steam, go back to the Pre-Installation step. If this still doesn't work, ensure that you are not running Wabbajack as an Administrator. DO NOT ASK FOR HELP WITH PIRATED GAMES ON THE WABBAJACK DISCORD.

**All downloads from Lover's Lab are failing.**

Lover's Lab is much more restrictive about automated downloads to users outside of the United States. Attempt to use a free- or budget- VPN with a terminus in the United States to automate your downloads. I personally recommend Proton VPN from _MIT_, it's free, has decent performance and maintains excellent privacy protections. If you do not have such an option, you will need to download the LL mods manually, as per the manifest section below.

**MEGA download cap exceeded.**

This shouldn't happen unless you download the list multiple times or download multiple Wabbajack lists. Sometimes it does anyway. Try signing up for a MEGA account, or if you have already done so, try logging out of it and downloading anonymously (although much more slowly). I can't tell you to do it, but a VPN _has been known_ to circumvent some of **MEGA**'s restrictions.

**Wabbajack cannot continue because of unknown files.**

Move your downloads folder outside of your _Licentia Directory_, ensure the _Licentia Directory_ is clear of all files, then close and restart Wabbajack. Be sure to point the downloads box to your relocated downloads folder.

## Post-Installation

**REDACTED.** _Licentia_ now makes use of the "Stock Game" feature, so there is no longer a need to download `enbseries` manually, nor to copy over Game Folder Files. Carry on!

Do keep in mind, though, that any changes that would normally be made to the _Skyrim Special Edition_ directory such as changing ENB for better performance, installing a ReShade, and so on, must now be placed in the _Licentia/Stock Game_ folder instead.

This does mean, also, that you can install any other list with this feature (Stock Game) and they will be completely independent of each other and no longer require changing out any files whatsoever. Enjoy _Licentia_ in your Man Cave, show _Living Skyrim_ off to mixed company!

## Preparing Your Page File

It should be no surprise that modlists such as these require vast amounts of resources to run properly, largely due to their size, but also because the code is out of date and no longer optimized for modern systems. As a result, you will need to configure a _very large pagefile_ on your computer, otherwise you will crash almost constantly due to running out of memory to load the multiple gigs of textures on screen at all times.

You will need at least a 40GB fixed-size pagefile for _Licentia._ This differs from many other Wabbajack modlists because _Licentia_ is really big. This is true even if you have 24+ GB of VRAM and 32+ GB of VRAM, I have a 3090 and a beefy rig and still need 40GB pagefile due to the way everything works.

To make these changes:

1. Hold down your **LEFT WINDOWS KEY** and press **R.*
2. Type in `systempropertiesadvanced` and press **ENTER.**
3. Under _Performance_ (near the top) click "Settings..."
4. Click the _Advanced_ tab (along the top)
5. Under _Virtual Memory_ click "Change..."
6. Uncheck _Automatically manage_ if it is checked.
7. Select your FASTEST solid state drive.
8. Click the _Custom size:_ radio button to put a circle in it.
9. Next to _Initial Size_ type 40960.
10. Next to _Maximum Size_ type 40960 as well.
11. Press the _Set_ button (kinda down and to the right)
12. Press _OK_
13. Press _Apply_ if it is available
14. Press _OK_
15. Restart your computer.

## Preparing the Game

The next step is to prepare the game for play. Navigate to the directory where you installed the modlist _Licentia_. Inside you will notice an executable file called _ModOrganizer.exe_. This file (the _Mod Organizer 2_ application) has already been automatically installed and configured by Wabbajack with all the necessary mods to run the modlist and does not need to be updated, replaced, or manually configured. Simply launch it to continue.

## Launching the Game

The rest must be completed after the game itself is launched. I recommend bringing up this readme on a portable device by navigating to [www.wabbajack.org](https://www.wabbajack.org) and referring to the Gallery. Anyway, Launch the modlist from the command which reads **SKSE**. If you receive a message that files are missing, do not exist, or a warning about an incorrect path, you _may_ have to edit the link to "skse_loader" in the drop down and point it to your Skyrim directory. Once you are in-game, create your character and follow _all_ of the instructions in the below link:

# PLEASE CLICK THE BELOW LINK TO CONTINUE THIS ESSENTIAL README. THEN RETURN HERE TO COMPLETE THIS ESSENTIAL README.

[Licentia MCM Configuration And More](https://github.com/cacophony-wj/LeS/blob/master/MCMs.md)

## Updating the Modlist

Many times newer versions of _Licentia_ will require an updated version of _Wabbajack_, otherwise you will receive an image of a knocked-out Sheo with the message "Corrupted Modlist." Therefore, please ensure that you run _only_ the `Wabbajack.exe` located in the root of your _Wabbajack_ directory, not any of the executables in the archives or version directories (such as _2.5.0.9_). When you do so, _Wabbajack_ will automatically update to the latest version if necessary. 

Then simply re-download the modlist from the Gallery and specify the same directories you did the first time. Then check the "Overwrite" box. This will _delete_ any customizations you have made to the modlist _unless_ you change the names of the folder(s) they are located in. More on this below.

It is rarely recommended to continue a save when you update a modlist because _Skyrim_ super doesn't like it when you do that. Only update on a current save if you wish to start the game over, or if there is some horrible bug with it. In the latter case, I can often write a patch to fix your problem without necessitating a new save. Ask me on my private server. Just to confirm, _none of your save games will be deleted_ when you update. 

## Removing the Modlist

You can just remove the _Licentia_ folder and be done with it. SKSE and ENB files will still be in your game folder so I recommend using [ENB and ReShade Manager](https://www.nexusmods.com/skyrimspecialedition/mods/4143) if you want to remove the ENB.

## Contact

I am regularly available on [my discord server](https://discord.gg/jolly-coop).

If you enjoyed playing this modlist and feel that your time spent with it was worth any amount of money, consider donating to me in any amount of one dollar or more via my [Patreon](https://www.patreon.com/cacophony1979) or my [Ko-Fi](https://ko-fi.com/cacophony1979). Your donation will better the quality of my life and ensure that I can spend more time improving _Licentia._ There are no expectations for a recurring subscription, donate one dollar and immediately cancel if you wish. You will also receive benefits such as access to my Discord server's VIP channel where my friends and _Wabbajack_ staff talk shop. Finally, a portion of all proceeds will be forwarded as donations to various signature modders featured in _Licentia_, given that it could not exist without them. If you particularly enjoy a mod in my list, please consider _Endorsing_ that mod. If you login to _Nexus_ via _Mod Organizer,_ all you have to do is right click that mod and select "Endorse." 

**All variant profiles are currently on hiatus due to a bit of burnout on my part.** They **MAY** return at some point in the future.

## Contributing

See [Contributing](CONTRIBUTING.md).

## Changelog

See [Changelog](CHANGELOG.md).
