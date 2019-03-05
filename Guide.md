# Introduction

//todo

# Baseline Setup

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

If later while testing, this fails complaining about a missing MSVCP50.DLL, you can get it [here](https://www.dll-files.com/download/5cd93690f8028ab0361cdcd6d0373195/msvcp50.dll.html?c=UVFwS20yblJzS0NxZGJMNWxBbkVrdz09).

(I've only encountered this in the RIP version, not the installed version)

There are several bugs which I'm almost 100% certain *only occur on the ripped version* after testing in both. So again, I *do not recommend this approach*! Just download the ISO, and run the installer. 

**After main installation Method 1 or 2:**

So now we need the power of [dgVooDoo2](http://dege.freeweb.hu/dgVoodoo2/dgVoodoo2.html). This is an interface that talks to applications and kind of emulates the types of graphics outputs they're expecting, so they can work with modern computers. Once extracted, copy all 3 files from the MS (microsoft) folder into your Mechwarrior 3 folder. You can place the dgVooDoo setup application wherever you like, but personally I just leave it in the Mechwarrior 3 folder. 

You're going to need to go to the top of the application, where the "Config Folder/Running Instance" note is. On the right is a button that says "Add". This allows you to add profiles for each game you want to use DGVooDoo for. 

Make one for Mechwarrior 3, by pointing it at your MW3 folder. This will put a config file in your Mechwarrior 3 folder, if you've done it correctly. (dgVooDoo.conf)

Now what settings do I use for dgVooDoo? 

General:

* Adapter(s) to use/enable: your current GPU
* Full Screen Output: "Display 1"
* Scaling mode: Streched, keep aspect ratio
* Appearance: Enumerate refresh rates

DirectX:

* VRAM: 1024 MB
* Filtering: Force anisotropic 16x
* Resolution: Your current resolution, 59/60Hz
* Antialaising (MSAA): 8x
* Miscilaneous: Bilinear blit stretch, force Vsync

The scaling mode setting in General and the resolution setting in DirectX effectively negates the need for Teleguy's HD/Widescreen patch. However, as an added benefit, this method keeps the HUD the same scale as it was in the original game. Now you can play at as high as a resolution as you want, with no tiny hud!

Do **not** enable any compatability options for Mech3.exe. This *will* fuck up dgVooDoo. You may see crashes, extremely low framerate or otherwise. Let dgVooDoo do its job. 

**Framerate:** 

Mechwarrior 3 is another older game in which physics calculations are tied (somehow) to framerate. If you followed the steps above, hopefully the game should be capped via Vsync to 59Hz. However, if you force-disabled this in your drivers for all games, it won't work. (Obviously)

You can also use [RivaTuner Statistics Server](https://www.guru3d.com/files-details/rtss-rivatuner-statistics-server-download.html) to cap it to 30. This is also what I use to cap Skyrim to 60 to avoid similar issues. 

# End of Baseline, Beginning of Mods

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

# Known Issues

* The MFBs on Op 2 Mission 2 (possibly some other missions) get stuck. This happens if they are used to repair at their starting point. Once you've been repaired, you'll find 2 of the 3 MFB's no longer respond to commands to move. This can be fixed by hitting escape, going into the options menu, and then going back into the mission. Once you do so, they'll un-stick and get moving to their point. 

* Some missions, like Operation 1 Mission 2, have a bug related to save-games. If you start the mission, take some damage, and then repair, you took armor out of your total armor supply. However, this also magically carries over to *before you started the mission*. Meaning that if you try and fail to do Mission 2 several times, you'll quickly find yourself starting the mission with no armor at all. The best fix is to just back up your save file at the beginning of each mission. If you fail it, delete your save and get the backup. This also applies to ammo. Several missions apparently have this bug. Making the saves read-only may also be a potential fix. I haven't tested to see if this bug persists in an installed (non-rip) version of the game. 

* Launching the game as administrator will cause OBS hotkeys like starting a recording to fail. Why? No clue. But I've done extensive testing, it's very consistent.

* Alt-tabbing doesn't seem to do anything. Teleguy has an alt-tab registry fix that needs to be looked into

* No audio in the salvage screen (everywhere else appears fine)

* Binding keys in the controls menu seems iffy. Often need to press keys several times. 

# Contributions

A massive thank you to /u/dei-ex-machina for making the original guide that inspired me to do this one.

* AncientxFreako for his amazing mods that vastly improved the Mechwarrior 3 world
* PP Mguire for his technical assistance and explanations, as well as general advice
