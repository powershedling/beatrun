# beatrun
Modified beatrun's source code.<br><br>
There are lua modules, they are for Discord Rich Presence to work, if you want pure Lua just don't extract them, but your Level and Map will not be shown in your Discord status.<br>
This version of the beatrun works on any version of the game (Chromium or not).

# Installation
**1. Delete or disable VManip (Base) that downloaded from Workshop!**
**2. Delete `beatrun` folder in *addons* if you have one!**
3. Extract `beatrun` and `vmaniprework` folders to *your_game_folder/garrysmod/addons*.
4. Extract `lua` folder to *your_game_folder/garrysmod*.
    * `lua` folder constains modules for Discord Rich Presense to work. They are open source, visit [this](https://github.com/fluffy-servers/gmod-discord-rpc) to see the source.

## Changes added by me
* [Custom online courses database](https://courses.beatrun.ru)! It's free 🤯!
* Allow Overdrive usage on the server - `Beatrun_AllowOvedriveInMultiplayer`.
* Toggle between old and new (like in ME) Kick-Glitch - `Beatrun_OldKickGlitch`.
* Change HUD's colors - `Beatrun_HUDTextColor`, `Beatrun_HUDCornerColor`, `Beatrun_HUDFloatingXPColor`.
* Discord Rich Presence (extract `lua` folder to `garrysmod`, along side with `addons` folder).
* Small camera punch when diving.
* Ability to remove ziplines that created with *Zipline Gun* - RMB.
* Removed your SteamID from right corner, because I can.
* Allow players to spawn props without admin rights - `Beatrun_AllowPropSpawn`.

## TODO
- [X] Configurations menu
- [ ] Gamemodes menu

## Fixes and changes from previous version
* Hopefully fixed a bug with sliding/diving and stucking in the animation. Let me know on Github Issues if you can reproduce it again!
* All mentioned issues with sliding or grapple fixed with new VManip version.
* You can now dive to your death =)
* Kick glitch version toggle.

# All changes and fixes
* Course saving works with compression and without.
* Quick turnaround only with `Unarmed`.
* Fixed leaderboard sorting in gamemodes.
* Fixed grapple usage in courses and gamemodes.
* Fixed DataTheft crash when touching data bank.
* Fixed error when loading course.
* Fixed collisions issues.
* Fixed and tweaked player-player weapon damage.
* Proper Kick Glitch (Like in original ME: https://www.youtube.com/watch?v=zK5y3NBUStc)
* Grapple fixes. Now it moves with entity it attached to and other players can see it.
* More reliable grappling.
