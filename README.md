# 12/13/2022 update
to avoid unnecessary overlaps, please don't send names from the latest update until i do the first pass of names

# V-Tunable-Names
![Hi!](https://cdn.discordapp.com/attachments/743624986371293193/999970648598269992/monika2-sticker2x.png)<br>This is a page attempting to resolve and list all tunable names for the 5th major iteration of a certain crime game. **This is strictly for educational/research purposes only and I <ins>do not</ins> condone any potentially-malicious use of it.**

## Notes
- tunable_list.txt contains all currently known names for convenience.
- system_tunables.txt contains all currently known names for "system" tunables. Not sure where those are stored. Executable? Those are typically used for CD_GLOBAL, but can be used for anything, one such example being MP_GLOBAL.
- fake_tunables.txt contains tunables that have been long-removed or never existed to begin with but were still caught being used in the json for *whatever* reason.
- I am only a human and small mistakes or hash collisions can happen. If you believe you've noticed either of those, feel free to let me know.
- -----
- gen7-b*x*-additions contains known/solved names or hashes names that were added in an update of the respective build number for Xbox 360 and PS3 **only**. Mostly redundant as there's barely any difference between gen8-onwards.
- gen7-b*x*-removals contains known/solved names or hashes that were added in an update of the respective build number for Xbox 360 and PS3 **only**. Mostly redundant as there's barely any difference between gen8-onwards.
- gen8-b*x*-additions contains known/solved names or hashes that were added in an update of the respective build number for PC, PS4, and XO.
- gen8-b*x*-removals contains known/solved names or hashes that were added in an update of the respective build number for PC, PS4, and XO.
- gen9-b*x*-additions contains known/solved names or hashes that were added in an update of the respective build number for PC (post-3/15/22), PS5, and XSX|S.
- gen9-b*x*-removals contains known/solved names or hashes that were removed in an update of the respective build number for PC (post-3/15/22), PS5, and XSX|S.
- gen*x*-b*y*-*z*.hashes contains all hashes added or removed in an update of the respective build number for the respective generation.
- gen*x*-b*y*-*z*.txt contains all known/solved names added or removed in an update of the respective build number for the respective generation.

Contributions are welcome. The more names the merrier! However, please ensure that the names are added to the correct build file (or just dump them all in the full list file and I'll sort it later, though that might take a while). **DO NOT** submit custom names that don't match any hashes, and please be mindful of hash collisions!

## Contexts
All tunable contexts, might be useful.

Main contexts. Those seem to be always used.
- BASE_GLOBALS
- CD_GLOBAL
- MP_GLOBAL
- MP_FM_MEMBERSHIP

Dynamic contexts. Those are suffixed with the respective contentLists index.
- CONTENT_MODIFIER_
- CONTENT_MODIFIER_MEMBERSHIP_

Misc. contexts. Typically used for gamemode-specific changes, eg to disable snow in stunt races specifically, etc. Rarely used. Some are unused altogether.
- MP_CNC, MP_CNC_TEAM_COP, MP_CNC_TEAM_VAGOS, MP_CNC_TEAM_LOST
- MP_FM, MP_FM_DM, MP_FM_SURVIVAL, MP_FM_BASEJUMP, MP_FM_CAPTURE, MP_FM_LTS, MP_FM_VERSUS, MP_FM_GANG_ATTACK
- MP_FM_MISSIONS, MP_FM_HEIST, MP_FM_CONTACT, MP_FM_RANDOM, MP_FMADVERSARY
- MP_FM_RACES, MP_FM_RACES_CAR, MP_FM_RACES_BIKE, MP_FM_RACES_CYCLE, MP_FM_RACES_AIR, MP_FM_RACES_SEA, MP_FM_RACES_STUNT

## Special Thanks
You're probably here if you helped me out directly or at some point posted old plaintext copies of the json that had names I didn't have.
- [alloc8or](https://github.com/alloc8or)
- [FoxySnaps](https://twitter.com/FoxySnaps)
- [GTAOBOT](https://twitter.com/gtaobot)
- [RDO.GG API](https://rdo.gg/api)
- [root-cause](https://github.com/root-cause)
- [Tez2](https://twitter.com/TezFunz2)
- [yasmasdas](https://github.com/yasmasdas)
- ...and anyone else I might not have listed here.
