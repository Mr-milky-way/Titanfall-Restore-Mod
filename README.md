# Titanfall 2 Restore Mod
Titanfall 2 was released with a lot of cut code, this mod aims to add back this cut functionality

# Installation 

For this you are going to need
- A copy of titanfall 2
- Northstar Client

Download the version you want from the release page and add it to the mod directory of northstar

In order the get the best out of this mod use the launch commands of 
```
-dev +developer 1 +enable_debug_overlays 1 +cl_showpos 1 +ns_prefer_datatable_from_disk 1
```

# Features n Stuff
- Added ```SetBugReproNumber``` command
- Fixed Devmeun
- Added Gauntlet run recording playback (Still no recording though)
- Added back ```Trailer - Drop``` start point on Tday
- Added back Cut effect and cause rack titans mechanic (From @Nextracer1)
- Added back Unused BT prowler attack setpiece (From @Nextracer1) Finnished ainms may come at somepoint
- Added back Abyss 1 intro fight (From @Nextracer1)
- Added back Gauntlet ending effects (From @Nextracer1)
- Added back Skybridge jumpscare on effect and cause (From @Nextracer1)
- Added back Unused gauntlet ghosts (From @Nextracer1)
- Added back Draconis takeoff blastback (From @Nextracer1) but with a fix by me
- Added back and FIXED (mostly) Ark testing sequence(s)
- Added back NPC nagging on the Beacon
- Added back flack guns on Tday
- Added back and FIXED the werid difficulty mechanic
- Other little goodys

# BugReproNumber commands
These are the value(s) to change stuff around using the ```SetBugReproNumber``` command I added.
Run it in the command line like ```SetBugReproNumber <Input Number here>```

## Ship to Ship
- MaltaWidow_DevTest on ship to ship is BugReproNum 5 set with command. This is the same value for printing the malta origin. And for printing the 64's delta and angles when breaching.
- Stopping the spawn of thermite titans when fighting viper on ship to ship is BugReproNum 101
- For OLA and MALTA position print is BugReproNum 20
- IF BugReproNum IS NOT 0 AT THE END OF SHIP TO SHIP YOU WILL GO BACK TO WHEN YOU ARE IN THE ARC CONTAINER AND NOT CHANGE LEVELS
## All
- Rodeo Test is BugReproNum 7205 (basicly makes rodeos do nothing and just kinda puts you up there)
## Beacon Spoke0
- For SonicRun_FullyAnimated in Beacon Spoke0 use 81765 (Makes the fan thingy at the end of beacon 2 out of your control)


Thanks to [@Nextracer1](https://www.youtube.com/@Nextracer1) for inspiring this idea (and for some code (Most has been modified))

Feel Free to make a pull request anytime!
