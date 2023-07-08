# Worlds of Wonder MC

**Decent desc coming soon**

## Features:
 + Generally (survival)
   + Crafting tables
   + Furnaces
   + Chests
   + Tools:
     + Wood, stone, iron, gold, diamond
       + Shovel
       + Hoe
       + Sword
       + Axe
       + Pickaxe
     + Iron
       + Bucket (air, water, lava, powdered snow)
       + Shears
       + Flint and steel
   + Torches & lanterns
   + Buckets
   + XP bar
   + Health bar
   + Oxygen bar
   + Hunger bar
 + Overworld (survival)
   + Biomes (plains, snowy plains, jungle, bamboo forest, ocean)
   + Trees (oak, birch, jungle)
   + Giant jungle trees
   + Bamboo trees
   + Lakes & oceans
   + Ores (clay, coal, iron, copper, redstone, gold, lapis, diamond)
 + Nether (creative as portals don't work yet)
   + Biomes (regular, warped forest, crimson forest, lava ocean)
   + Warped trees/vines/roots/flowers
   + Crimson trees/vines/roots/flowers
   + Lava oceans
   + Lava rivers (sort of)
   + Ores (nether gold, quartz, ancient debris)
 + Creative
   + Spawn eggs (cow, pig)
   + Netherite tools
   + All the colors of everything
   + Cheats
   + 
## To-Do List
 - [ ] Make adjacent glass blocks/panes merge inner borders
 - [ ] Make block damage only activate on direct collision, not on the blocks around
 - [ ] Make magma only hurt when not crouching, and remove drowning
 - [ ] Enable spectator shortcut "L" in survival when cheats are enabled
 - [ ] Change default "release pointer for skreenshot" key to a more accessible key (k)
 - [x] Add goldPickaxe to breakTypes
 - [x] Migrate images, fonts, panoramas to local file
 - [x] Migrate music disc sound to local file
 - [ ] Migrate sounds, music to local file
 - [ ] Make the textures originate from a texture atlas
 - [ ] Make ores spawn in veins
 - [x] Add hidden command to toggle cheats (cheats true/false)
 - [ ] Creation menu:
   * [ ] Add cheats switch
   * [ ] Make it work
   * [ ] Add bonus chest option
   * [ ] Make it work
 - [ ] Make some blocks (bedrock, obsidian, nokia, etc.) immune to TNT
 - [ ] Make mobs (cows, pigs) take block damage like the player (lava, magma, cacti, wither roses, etc.)
 - [ ] Make mobs NOT LOOK LIKE WOOL PLEASE
 - [ ] Make mobs spawn naturally
 - [ ] Pare mobs's jump heights down to 1,25 (jump over blocks with more ease but not over fences)
 - [ ] Implement at least rudimentary mob pathfinding
 - [ ] When a mob is dead, tell it to stop moving around
 - [ ] Up fences's hitbox heights to 1,5
 - [ ] Limit what forms can different blocks take (fences, slabs, stairs) to shorten the enter cycle and to actually not have pickaxe stairs
 - [ ] When (`SHIFT`) is pressed while on a ladder, make player remain stationary
 - [ ] Add blocks:
   * [ ] Sea life blocks like coral (blocks, fans, coral)
   * [ ] Candles
   * [ ] Bamboo (block, strippes block, mosaic, door, trapdoor)
   * [ ] Sea pickle
   * [ ] Froglights (yellow, green, purple)
 - [ ] Make leaves despawn when not close to wood (and drop stuff)
 - [ ] Make some items/blocks not appear on the creative inventory (like SW logs)

### **Crafting**
 - [ ] The rest of the workbench crafts (smithing table, anvil, loom)
 - [x] Fence gates
 - [x] Blast furnace
 - [ ] TNT

### **Overworld**
 - [ ] Add clouds
 - [ ] Dungeons with loot chests
 - [ ] Desert lava lakes
 - [ ] Underground lava/water lakes
 - [ ] Raveens
 - [ ] Rivers
 - [ ] Make pockets of powdered snow on the snowy plains biome
 - [ ] Implement biomes:
   * [ ] Decent mountains
   * [ ] Ocean coral reef biome (with actual coral structures)
   * [ ] Roofed forest
   * [ ] Taiga (for spruce trees)
   * [ ] Savanna (for acacia trees)
   * [ ] Dark oak forest (for dark oak trees)
   * [ ] Mesa (badlands)
   
### **Nether**
 - [ ] Make a return portal when traveling for the first time
 - [ ] Add nether mobs
   * [ ] Blazes
   * [ ] Endermen
   * [ ] Nether skeletons
   * [ ] Magma cubes (implement the splitting into smaller cubes)
   * [ ] Ghasts
   * [ ] Maybe piglins, brutes, hoglins, zoglins, etc.

### **End**
 - [ ] Make the Ender portal mechanics
 - [ ] Add it (flatter noise for the top and a steeper noise for the underside)
 - [ ] Add the pillars
 - [ ] Add the spawn platform
 - [ ] Add a return portal
 - [ ] Add a ton of endermen

## Bugs:
 - [ ] Even when there is a stack in the inventory, new items always appear on the hotbar
 - [ ] Even when there is a stack in the hotbar, new items always appear on the first empty slots available
 - [ ] Water sides are visible on chunk borders (from the outside of the water)
 - [ ] The 1 pixel lower water behaves in strange ways
 - [ ] At high speeds and/or lots of lag, falling items and blocks can phase through blocks
 - [ ] If TNT explodes near water (but not in it), it will explode the water (weirdest sight I've ever seen)
 - [ ] P.S.: Yes, I did learn the last two while exploding my world to death with hundreds of TNT
 - [ ] Sometimes cacti don't understand when to stop and grow incontrollably (hundreds of blocks)
 - [ ] P.S.: The worst part is you can't collapse the massive things for fear of the PC self-descructing
 - [ ] Blocks that are not full blocks (stairs, torches, flowers, ladders, etc.) that are right next to a truly full block, their adjacent face turns black (100% shadow or something). Inverse happens with 1 pix lower solid blocks (path blocks, soul soil..)

### Stupid bugs I caused while messing arond:
 - [ ] Font (VT-13) doesn't work
 - [ ] Skin doesn't work, leaving the character a silvery gray all-over
 - [ ] Commands don't work - every time they freeze the game "too much recursion"
 - [ ] I made bedrock breakable and have no idea how to undo it
 - [ ] For some reason the two furnace crafts (stone, cobblestone) don't work

## Stuff
 - Did you know that 7 sticks can smelt 3.5 items, but as ladders they can smelt 4.5?
 - Amazingly, if you try igniting a 3 by 3 cube of TNT, it will turn into diamonds instead of exploding - try this in your house sometime.
 - Make a shovel with two copper ingots and an amethyst shard and you will get a spyglass! It even works! (Only 1% know this craft)
 - Golden swords are actually really OP... Not kidding. But it's not like you can use them anyway.

## FAQ
 - Q: Yo dude the trees have no trunks
   - A: Um well you can always chop down dead bushes i guess
 - Q: Why is it so cringey when the font looks like that?
   - A: I will fix that. really
 - Q: How do I change my controls cause I'm going to set everything to the same key
   - A: PLEASE NO
 - Q: How do I light TNT
   - A: With other exploding TNT
 - Q: Is there a Herobrine
   - A: Of course not
   - A: There _is_ a Slenderman jumpscare though
 - Q: Why are my cactuses on steroids
   - A: On the bright side you don't need to make farms!

## Credits
This project was originally from Thingmaker's Minekhan, also inspired by the following:
 - [Hacker1234's MineKhan-modded](https://github.com/Hacker1254/MineKhan-Modded)
 - [Thingmaker's MineKhan](https://thingmaker.us.eu.org/)
 - [Willard's MineKhan](https://willard.fun/minekhan/)

## Disclaimer
All textures are copied 100% from Minecraft, property of Notch, with whom I have no association whatsoever.
