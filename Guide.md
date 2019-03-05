#Introduction

//todo

#Baseline Setup

**1:** Get the ripped version of Mechwarrior 3 from [here](http://www.myabandonware.com/game/mechwarrior-3-7pg#download).

**2:** Get the ISO file as well, it'll be important later for applications like the Patcher that require a CD to be there.

**3:** Do *not* get the NO CD Fix. Why? You see, the No CD fix is actually just a modified executable for MW3, based off of the 1.2 patched version. This is great on its own. 

However, you'll end up losing this fix once you install other things that replace the Mech3.exe, so it's kind of pointless. Specifically, Teleguy's HD/Widescreen patch over-writes this. You can *manually* patch the EXE, but it's not really recommended. You have the ISO file, just use it. Patching the NO-CD version of the EXE on your own is likely more trouble than it's worth.

**4:** Get the 1.2 Patch (also from MyAbandonware). This is an executable that will put several files on your computer, including the 1.2 patched Mech3.exe, as well as several other misc. files that are important. Now listen carefully: This does not work the way you think it does. By default, if you haven't run the Registry Setup executable in the Mechwarrior 3 - RIP folder, it will default to C:/Microprose/Mechwarrior 3. 

However, the moment you run the Registry setup, you are effectively telling your computer where Mechwarrior 3 is installed. So if you do the registry setup first, and *then* do the 1.2 patch, you won't need to move any files. The patcher will *automatically* put the files in the correct place. 

But if you didn't run the registry setup first (which is fine) you just need to find where the patch files are, and move them to your current folder for MW3. If you ran the Registry setup somewhere else previously (like a different drive) you may find the files are there instead.

**5:** So now you have Mechwarrior 3 installed, a CD so it doesn't complain, and the 1.2 patch correctly installed. However, Mechwarrior 3 is based off of older tech and doesn't play nice with modern computers. 

So now we need the power of [dgVooDoo2](http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2.html). This is an interface that talks to applications and kind of emulates the types of graphics outputs they're expecting, so they can work with modern computers. Once extracted, copy all 3 files from the MS (microsoft) folder into your Mechwarrior 3 folder. You can place the dgVooDoo setup application wherever you like, but personally I just leave it in the Mechwarrior 3 folder. 

You're going to need to go to the top of the application, where the "Config Folder/Running Instance" note is. On the right is a button that says "Add". This allows you to add profiles for each game you want to use DGVooDoo for. 

Make one for Mechwarrior 3, by pointing it at your MW3 folder. This will put a config file in your Mechwarrior 3 folder, if you've done it correctly. (dgVooDoo.conf)

Now what settings do I use for dgVooDoo? Under the DirectX tab (since MW3 is a directX game) I'd disable the dgVooDoo watermark and enable MSAA. 8x MSAA removes a lot of the aliasing, though it's not perfect. I also allow for 1024MB of Vram, though I doubt this actually does anything.

Other settings are up to you to try and test. I haven't seen any real difference from any of them, but it might be worth a shot. Do not set the resolution here, that is handled by the launcher.

**6:** Cap your FPS to 30, somehow. Preferably with [RivaTuner Statistics Server](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html). This is also what I use to cap Skyrim to 60 to avoid similar issues. 

You need to do this because as with many games (even modern ones) the physics engine's calculations are tied to the framerate you're playing at. At 60 FPS you'll see bouncing APCs. 30 FPS, while not ideal, works perfectly. 

**7:** Now is the most important part - Go ahead and test starting the game. If it fails complaining about a missing MSVCP50.DLL, you can get it [here](https://www.dll-files.com/download/5cd93690f8028ab0361cdcd6d0373195/msvcp50.dll.html?c=UVFwS20yblJzS0NxZGJMNWxBbkVrdz09).

It's possible that this fix may be the source of other issues, but it's an unknown factor at this point. 

If you're having any issues at this point, make sure you followed all the instructions so far correctly. If you did and you're still having issues, message me. It should work at this point for everyone.

Do **not** enable any compatability options for Mech3.exe. This *will* fuck up dgVooDoo. You may see crashes, extremely low framerate or otherwise. Let dgVooDoo do its job. 

**8:** Wouldn't it be nice if Mechwarrior 3 could play at a higher resolution and 16:9? Yes, it would. And there are two main options you have:

* [Teleguy's HD/Widescreen Patch](https://www.vogons.org/viewtopic.php?f=24&t=42714)

* [Res Fix by EOP](http://www.mechwarriorsunited.com/downloads.html)

Both of these replace the executable. (And both are based on the 1.2 patched version, so don't worry) However, Teleguy's is a better option overall. It offers support for a wide range of resolutions, it fixes the 4:3 fixed aspect ratio, and it seems to just work well. (EOP's is fixed at 1024x768, which is not 16:9)

Go ahead and extract the files, moving all of them into your Mechwarrior 3 folder. 

*You'll need to run the Launcher is administrator, otherwise it won't find the Mech3.exe.*

As Dei Ex Machina said, high resolutions aren't really an option. Even not considering other issues, the game's UI and zoom are far, far too small at 1080p or 1440p.

1600x900 is acceptable, but I've found that I personally prefer even lower, 1280x720, just so the zoom reticule is large enough to matter and so the UI isn't so damn small.

Personal preference, but that's what I'd suggest.

Note: Once you've done this, don't mess with the resolution in-game. It'll work, but then you'll be playing at whatever you select there instead. And it doesn't have 16:9 options. 

I don't know if you need to launch the game from the launcher every time, or if you need to select the resolution every time. However, I do both just in case. 

**END OF BASELINE:**

Congrats! This setup should work fine on modern machines, and won't have any really serious issues.

Again, message me if you have anything going on after following these steps. This should work fine.

However, do some of you want **more**? Did you find the campaign far too easy? The enemies and your lancemates too braindead? The weapons too painful to use or worthless? The missions too simplistic? 

May I suggest:

#Additional mods you may want to try (and some important notes regarding them)

Downloads can be found here: http://mech3mod.weebly.com/blog

Note: None of these mods replace the Mech3.exe executable. Please very carefully read the message on each mod before installing them, and the readme if you can. Don't make the mistakes I did. 

* Mechwarrior 3 HD Skins 

It's what it says on the tin. HD skins for several 'Mechs in MW3. Not all 'Mechs and all skins are affected, but it does get many. I'd certainly suggest trying this.

Note: This will either work with Vanilla MW3, or the Weapons Mod 2.3 or earlier. **If you have Weapons Mod version 2.4 or newer, it comes with this skins pack**

Also: It adds some extra things to the game, including messages in each map briefing (visibility, hazard info, etc). 

* Mechwarrior 3 Weapons Mod 2.4/2.45

This both modifies and replaces many of the weapons in Mechwarrior. Autocannons are single-shot. MGs are faster, more damaging and more accurate. Pulse lasers fire far differently. **I cannot overstate how damn good this mod is.** Seriously give it a try. 

Note 1: You *need* to install the 2.4 weapons mod first before the 2.45 patch. You can't just install 2.45 on its own.

Note 2: Just like how Skyrim has a limited number of skill trees (no more, no less) Mechwarrior 3 has a limited number of weapons. If you want a new weapon in the game, you'll need to replace something. Because of this, several weapons/electronics/additions are replaced in this mod. You can find the specifics in the readme or on his site, but just something to be aware of.

Note 3: This one does more than it says on the tin. If you load up Op 1, Mission 2 you'll find that the turrets no longer have a max degree they can turn to. Approaching from the south *is* a death trap. You'll need to go northwest to the bridge and hit them where they can't hit you due to terrain. More changes like this may happen throughout the game. 

Note 4: It's mentioned that if you're installing this mod, you shouldn't install The reader.zbd file from Teleguy's HD/Widescreen patch. Just note that while this is true, if you install the weapons mod afterward, it really doesn't matter. It'll be overwritten and work fine. 

*  Mech3 Single-Player Campaign Added Enemies V 1.1

This is not the Mechwarrior 3 you remember. This is a devastatingly brutal modification to the campaign. More enemies, smarter enemies, better equipped enemies with better guns. (Assuming you're using the weapons mod).

You will need to learn the layout of the map, do weird maneuvers and play far differently than you did before. Cheese to the absolute maximum you can to survive. Don't play fair. Op 1 Mission 2 will completely annihilate you until you figure out how to do it properly. 

(If you can't handle it, which is *very* understandable, there's a version without the additional enemies that you may want to try. It's still certainly a challenge.)

#Known graphical, gameplay, and otherwise issues you may encounter

* Moving objects, like the MFBs, may show signs of something like Z-fighting or texture flickering. Do you see the insides of the MFB kind of slide in and out of view as they roll by? If so, this is it. No known fix at this time, but *please* let me know if you're not encountering this so we can narrow it down. It may be an inevitability of dgVooDoo, but I'm unsure.

* The MFBs on Op 2 Mission 2 (possibly some other missions) get stuck. This happens if they are used to repair at their starting point. Once you've been repaired, you'll find 2 of the 3 MFB's no longer respond to commands to move. EDIT: This can be fixed by hitting escape, going into the options menu, and then going back into the mission. Once you do so, they'll un-stick and get moving to their point. 

* Text in the UI looks like garbage, if it's not on a solid background. For example, the weapons list in the top right is basically unreadable most of the time. However, if I move the camera up so it's in front of the top of my 'Mech (on a solid background) it's perfectly readable. No known fix. 

* Attempting to control-alt-delete may cause the game to go to a black screen. You won't even see the Windows options, you'll just be stuck there. Only fix is a restart. 

* Some missions, like Operation 1 Mission 2, have a bug related to save-games. If you start the mission, take some damage, and then repair, you took armor out of your total armor supply. However, this also magically carries over to *before you started the mission*. Meaning that if you try and fail to do Mission 2 several times, you'll quickly find yourself starting the mission with no armor at all. The best fix is to just back up your save file at the beginning of each mission. If you fail it, delete your save and get the backup. (EDIT: This also applies to ammo. Several missions have this bug)

* Launching the game as administrator will cause OBS hotkeys like starting a recording to fail. Why? No clue. But I've done extensive testing, it's very consistent.

* In-game resolution is different than in-menu resolution. If recording with OBS, force scaling to the same resolution as you set in the launcher.
