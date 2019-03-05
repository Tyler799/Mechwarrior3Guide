#Introduction

//todo

#Baseline Setup

First and foremost, if you already have an installation of Mechwarrior 3 take the time to properly uninstall it. If you just have a ripped version then you don't need to use the Windows add/remove programs tool, but you should still go and delete the folder. 

As for installation, there's two main methods. I recommend the first one:

**Method 1: (Recommended)**

1: Download the ISO for Mechwarrior 3 [here](http://www.myabandonware.com/game/mechwarrior-3-7pg#download) and the vrsion 1.2 patch.

2: Open the ISO, and run "Autorun.exe". This is the installer for Mechwarrior 3. Chose a location you want it to be installed to. As for options, I recommend:

* Enable the video file option
* Disable software rendering option
* Leave hardware-accelerated enabled, configure it and choose only "8MB" for the textures. (Not that it matters much)

4: Open the 1.2 patch download, and run the executable within.

5 (Optional): Download the "no CD" fix from that same site. This is an executable based on version 1.2 of Mechwarrior 3. Move it into the Mechwarrior 3 folder and over-write the original. Now you don't need the ISO anymore. 

**Method 2:**

1: Download the RIP for Mechwarrior 3 [here](http://www.myabandonware.com/game/mechwarrior-3-7pg#download) and the version 1.2 patch. Extract it wherever you like. 

2: Run the registry setup executable within. This also acts as the "no CD" fix.

3: Open the 1.2 patch download, and run the executable within.

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

* Mechwarrior 3 Weapons Mod 2.47

This both modifies and replaces many of the weapons in Mechwarrior. Autocannons are single-shot. MGs are faster, more damaging and more accurate. Pulse lasers fire far differently. **I cannot overstate how damn good this mod is.** Seriously give it a try.

Note 1: This includes the previously used HD Skins pack.

Note 2: Just like how Skyrim has a limited number of skill trees (no more, no less) Mechwarrior 3 has a limited number of weapons. If you want a new weapon in the game, you'll need to replace something. Because of this, several weapons/electronics/additions are replaced in this mod. You can find the specifics in the readme or on his site, but just something to be aware of.

Note 3: This one does more than it says on the tin. If you load up Op 1, Mission 2 you'll find that the turrets no longer have a max degree they can turn to. Approaching from the south *is* a death trap. You'll need to go northwest to the bridge and hit them where they can't hit you due to terrain. More changes like this may happen throughout the game. 

*  Mech3 Single-Player Campaign Added Enemies V 1.1

This is not the Mechwarrior 3 you remember. This is a devastatingly brutal modification to the campaign. More enemies, smarter enemies, better equipped enemies with better guns. (Assuming you're using the weapons mod).

You will need to learn the layout of the map, do weird maneuvers and play far differently than you did before. Cheese to the absolute maximum you can to survive. Don't play fair. Op 1 Mission 2 will completely annihilate you until you figure out how to do it properly. 

(If you can't handle it, which is *very* understandable, there's a version without the additional enemies that you may want to try. It's still certainly a challenge.)

#Known graphical, gameplay, and otherwise issues you may encounter

* The MFBs on Op 2 Mission 2 (possibly some other missions) get stuck. This happens if they are used to repair at their starting point. Once you've been repaired, you'll find 2 of the 3 MFB's no longer respond to commands to move. This can be fixed by hitting escape, going into the options menu, and then going back into the mission. Once you do so, they'll un-stick and get moving to their point. 

* Some missions, like Operation 1 Mission 2, have a bug related to save-games. If you start the mission, take some damage, and then repair, you took armor out of your total armor supply. However, this also magically carries over to *before you started the mission*. Meaning that if you try and fail to do Mission 2 several times, you'll quickly find yourself starting the mission with no armor at all. The best fix is to just back up your save file at the beginning of each mission. If you fail it, delete your save and get the backup. This also applies to ammo. Several missions apparently have this bug.

* Launching the game as administrator will cause OBS hotkeys like starting a recording to fail. Why? No clue. But I've done extensive testing, it's very consistent.
