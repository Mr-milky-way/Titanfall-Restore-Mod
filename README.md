# Titanfall 2 Restore Mod
Titanfall 2 was released with a lot of cut code, this mod aims to add back this cut functionality

# Demo/Images
You can find a demo [here](https://youtu.be/5W49T0Bcrn8) it's not everything but it's a lot of it.
<img width="2559" height="1439" alt="image" src="https://github.com/user-attachments/assets/e291eb8b-5a45-4224-8f27-562983ebe1f0" />
<img width="2474" height="1395" alt="image" src="https://github.com/user-attachments/assets/58ab1df8-6622-42fa-8425-a7c55f329e2b" />



# Installation 

## Requirements
For this you MUST have the following
- A legitimate copy of Titanfall 2
- Northstar Client (required for mod loading)

## Easiest Method (Recommended)
If you use Thunderstore mod manager you can install from [here](https://thunderstore.io/c/northstar/p/MrMilkyWay/Titanfall2RestoreMod/)
Thunderstore will handle the rest automatically

## Manual Installation
1. Download the desired version from the Releases page
2. Extract the archive
3. Place the extracted folder into: ```<YourTitanfall2InstallDir>/R2Northstar/mods```
4. Launch the game via Northstar
Note that you will have to check manually for updates

## Recommended Launch Commands
To get the full debugging and restored functionality, add the following launch options:
```
-dev +developer 1 +enable_debug_overlays 1 +cl_showpos 1 +ns_prefer_datatable_from_disk 1
```

# Features n Stuff
- Added ```SetBugReproNumber``` command
- Fixed Devmeun (still in need of adding some functionalty back)
- Added Gauntlet run recording playback (Still no recording though I may try to add that later idk how tho)
- Added back ```Trailer - Drop``` start point on Trial by Fire
- Added back Cut Effect and Cause rack titans mechanic
- Added back Unused BT prowler attack bit on Effect and Cause (Finnished ainms may come at somepoint)
- Added back Abyss 1 intro fight
- Added back Gauntlet ending effects
- Added back Skybridge jumpscare on Effect and Cause
- Added back Unused gauntlet ghosts
- Added back Draconis takeoff blastback on Trial by Fire
- Added back and FIXED (mostly) Ark testing sequence(s) (need to set bug repro Numbers see [#The Ark](#the-ark))
- Added back NPC nagging on the Beacon
- Added back flak guns on Trial by Fire
- Added back and FIXED the weird difficulty mechanic
- Other little goodies

# BugReproNumber commands
These are the value(s) to change stuff around using the ```SetBugReproNumber``` command I added.
Run it in the command line like ```SetBugReproNumber <number>```

## The Ark
- MaltaWidow_DevTest on ship to ship is BugReproNum 5 set with command. This is the same value for printing the malta origin. And for printing the 64's delta and angles when breaching.
- Stopping the spawn of thermite titans when fighting viper on ship to ship is BugReproNum 101
- For OLA and MALTA position print is BugReproNum 20
- Test_WidowJumpRecordingSetup is 2
- TEST_HangarIntro is 3
- TEST_HangarFightRecordingSetup is 4
- TEST_BreachRecordingSetup is 6
- TEST_BridgeRecordingSetup is 7
- TEST_DeckFx is 8
- TEST_GoblinModels is 9
- IF BugReproNum IS NOT 0 AT THE END OF SHIP TO SHIP YOU WILL GO BACK TO WHEN YOU ARE IN THE ARC CONTAINER AND NOT CHANGE LEVELS
## All
- Rodeo Test is BugReproNum 7205 (basicly makes rodeos do nothing and just kinda puts you up there)
- Some sorta Rodeo debug would be 112023 (looks to be something with view angles)
- Stop printing load progress is 196356
- Stop saving with 184641 (I think)
## Beacon Spoke0
- For SonicRun_FullyAnimated in Beacon Spoke0 use 81765 (Makes the fan thingy at the end of beacon 2 out of your control)
## Trial by Fire
- To stop a wait frame on into use 188170 (could break something idk)

Thanks to [@Nextracer1](https://www.youtube.com/@Nextracer1) for:
- Inspiration
- Original code contributions (Most code has since been modified or extended)


# Contributing

Pull requests are welcome at any time.
Restoration work, fixes, documentation, and discoveries are all appreciated.
