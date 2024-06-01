# Fallout NV Rampaging Giant Mod

Allows the player to grow into an invincible giant and stomp around as they please. It's also possible to eat things!

## Installation and Use

### What's Required?

- [xNVSE](https://github.com/xNVSE/NVSE/releases)   
- [JIP LN NVSE Plugin](https://www.nexusmods.com/newvegas/mods/58277)   
- [JohnnyGuitar NVSE](https://www.nexusmods.com/newvegas/mods/66927)  
- All Quest DLC (optional for main mod, but everything else uses them)

### Where Do Mod Files Go?

Files in "Fallout New Vegas" go inside the game's installation folder. They are batch files for activating aspects of the mod and ESPs for the mods themselves.

Files in "Mod Organizer 2" are intended to be placed in a Mod Organizer "mods" folder for simple categorization and activation. You could also place their contents into the game's Data folder if you don't have a program for organizing loose files, just make sure you know where everything goes.

### What Are the Mods?

**gtsMain** is the main source of everything to do with giant abilities. Contains very few minor overrides.

**gtsDeathDialogues** removes player pain sounds and NPC death quotes, but only while the player is giant. (WIP)

**gtsDestBody** makes every creature explodable while keeping most limbs intact. (WIP)

**gtsDestBodyYUP** is a compatibility patch for [YUP](https://www.nexusmods.com/newvegas/mods/51664)'s evolved centaurs for anyone using YUP. *This goes below YUP and gtsDestBody.*

**gFixedChanceSpawns** removes the random chance from most creature spawns. This makes overworld spawns a little more consistent, but numerous. (some may initially fail to spawn due to a global actor limit)

**gItemPorts** is the main place where I put most custom items, as well as adds a container that'll hold them.

**gItemPortsLoot** adds the ported FO3 weapons in gItemPorts to a few loot tables. *This goes below gItemPorts.*

**gTestSquish** adds creatures to a test map for debugging.

**Generic Edits** changes various little things. Moves a bad idle marker in the Canyon Wreckage, has my own attempt at fixing the infamous OblivionSpawnTestScript, adds a hidden damage buffing perk, gives Turpentine its unused icon, raises the player's max resistance and VATS chance, increases the player death reload time so you can watch a funny ragdoll, increases the VATS hit chance mult by 0.1 for some reason, nerfs the laser shotgun damage effect, and fixes the large and small dog audio templates from using mismatched sounds. Whew.

**CrittersToCoyotes** is an overhaul of [Critters to Coyotes](https://www.nexusmods.com/newvegas/mods/38281) that renames the critters, fixes their size, normalizes their speeds, and adds compatibility with the [Coyote Puppy](https://www.nexusmods.com/newvegas/mods/34972) mod (not required).

### What Are Those Batch Files?

These are files you can call with the ``bat`` console command to enable some options and become a giant. I do it this way because the console is quicker to access than going through menus to find an item. Maybe I'll make an MCM menu some time.

``rampage`` turns you into a giant. ``rampageUndo`` returns you to normal. The AL and BH files are for when I eventually set up playing as creatures.

``giantxp`` causes kills while giant to grant XP. ``giantxpUndo`` disables this. (on by default)

``birdsdontfly`` makes it so birds will not fly away while you're giant. ``birdsdontflyUndo`` makes them always fly away like normal. (on by default)

``essent`` will allow essential actors to die. ``essentUndo`` will make them knock out normally. (default is whatever you have it in your INI)

``border`` lets you walk past barriers that say, "You cannot go that way." ``borderUndo`` will reenable them. Not a lot of them in this game, though, but you can use [Ultimate Invisible Wall Remover](https://www.nexusmods.com/newvegas/mods/76546) to remove those and [World Map with Borders](https://www.nexusmods.com/newvegas/mods/65584) to know where the walls are.

``qt`` is a quick way to warp to the test map from the gTestSquish mod.

