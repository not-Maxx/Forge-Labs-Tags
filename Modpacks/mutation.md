**Disclaimer: Some of this information might be outdated, but it should give you a general idea on how to "mutate" the zombies. **

**How to enable zombies that can pillar up: **
1) Go to the config folder for Zombie Apocalypse
2) Look for the file named: `epicsiegemod.cfg`
3) Open the file and look around for `List of mobs that can pillar up and build stairs`
4)Look for the line that says `S:"Building Mobs" <` and put in `minecraft:zombie`so that it looks like `S:"Building Mobs" <minecraft:zombie`

**How to increase zombie speed: **
1) Go to the config folder for the Zombie Apocalypse 
2) Look for the file named: `roughmobs.cfg`
3) Open the file and around the middle of the file, there will be `speedboost`
4) Zombies won't be included in the config, so add `zombie,50` underneath `magma_cube,50`
5) Note that the "50" is the percent speed added, so the zombies will move +50% faster, and "100" making the zombies move +100% faster
*values may be incorrect, play around with them to see what you like*

**Here's how to "potentially" lower the amount of damage zombies do: **
1) Load up the modpack
2) goto `mods` with the green diamond
3) look for `thicc entities`
4) click on it and search for "zombies" 
5) Click on the 6th entry called `zombie`
6)You will see the config values for `damage` and `armor`
7) Default value for damage is 1
8) Default value for armor is 5