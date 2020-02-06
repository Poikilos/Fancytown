# Fancytown
This Minecraft 1.8 world is a torture test for world converters such as mcimport. Any code beyond mcimport may not be necessary, but Python should be used to match mcimport if any (for eventual merge).

## Player

### Player with UUID 5f7f4afea5d546b884f689ebe74bd4a5
The notes below are for the player with UUID 5f7f4afea5d546b884f689ebe74bd4a5.

#### Location
(15, 71, 238) (That is the location of the player's feet--the stored y value may vary)

#### Ender Chest
The ender chest of the player above contains:
- Sponge
- Wet Sponge
- Diamond Sword (Enchanted: Sharpness III)
- Enchanting Table
- Slightly Damaged Anvil
- Saddle

#### Armor
- Pumpkin [as helmet]
- Diamond Chestplate
- Diamond Leggings
- Diamond Boots

#### Inventory
9x3 plus 9x1 hotbar = 36 slots (plus 4 armor slots, each allowing only
the specific piece of armor) (`*` = in hotbar). See also:
`screenshots/2020-02-06_16.19.02.jpg`.
- (37) Oak Wood Planks [1x1x1 meter a.k.a. nodebox a.k.a. default:wood]
- Dispenser
- Minecart
- (3) Oak Wood Stairs
- Chain Chestplate
- (4) Spruce Sapling
- Gold Chestplate
- (2) Gold Nugget
- Hay Bale
- Oak Fence Gate
- Button [wooden]
- Acacia Sapling
- Lapis Lazuli [nugget version]
- Minecart [same kind as above]
- Minecart with Furnace
- Snow [1x1x1 meter]
- Snow ["carpet" style]
- (4) Chests
- (2) Chests [same kind as above]
- Sign [wooden]
- Snowball
- Sponge
- Wet Sponge
- Spruce Wood [trunk]
- Cyan Carpet
- Light Blue Carpet
- * (12) Note Block
- * Iron Horse Armor
- * Gold Horse Armor
- * Diamond Horse Armor
- * Piston
- * Chest [same kind as above]
- * Sign [sam kind as above]
- * empty slot
- * (2) Redstone Torches (becomes mese lamp)

## Items in World

### Water
Importing water close to original condition is important for preserving gardens.
A water source is at (-1, 67, 244) and extends to (-1, 67, 237).

### Pumpkin
The pumpkin is always carved, but there is an "uncarved" version
listed as an alternate in the Official Minecraft wiki. How to obtain it
is unknow. An unpicked pumpkin (naturally grown but still looks carved)
is at (-6, 68, 246), and one placed by the player is at (-6, 68, 242).
The Jack o' Lantern [lit] is a separate node, at (-4, 68, 242).

### Sign
A sign has an entity with it, perhaps to hold the text (interestingly, 
a cactus can not exist in front of a sign, because the cactus breaks, 
whereas normally a cactus damages all entities [converts  them into 
dropped item form if invincible]). A sign facing approximately -112 
degrees is at (0, 68, 254). The rotation is determined by an integer 
param of 0-15 (0 is South, 1 is South-Southwest, and so on).

### Armor Stand
An armor stand at (0, 68, 262) is wearing full diamond armor (helmet, chestplate, leggings, boots).

### Pistons
- Directly adjacent to (0, 64, 273) are 4 pistons, facing the four cardinal directions (one at (0, 64, 274) faces South, and so on).
- Directly adjacent to (-5, 64, 273) are 4 pistons that are activated (extended to 2x1x1 meters) in the same arrangement as above.
- Directly adjacent to (-10, 64, 273) are sticky pistions in the same arrangement.
- Directly adjacent to (-15, 64, 273) are activated sticky pistions in the same arrangement.
- A sticky piston facing up is at (11, 64, 274) and an activated one is at (11, 64, 274) extending to (11, 65, 274) 
- A piston facing up is at (11, 64, 272) and an activated one is at (11, 64, 271) extending to (11, 65, 271) 
- A sticky piston facing down is at (11, 68, 274) and an activated one is at (11, 68, 273) extending to (11, 67, 273) 
- A piston facing down is at (11, 68, 272) and an activated one is at (11, 68, 271) extending to (11, 67, 271) 
- An activated tripwire_hook facing South is at (18, 68, 267)
  - An activated tripwire_hook facing North is at (18, 68, 272)
  - String is between them (tripwire).

### More Items in World
- a Cobweb is at (4, 64, 277)
- a Trapped Chest at (4, 64, 278) contains: pumpkin
- a Chest at (4, 64, 276) contains: cobweb, chest, trapped chest
  - A chest inside a chest cannot contain anything, but **shulker 
    boxes**, which also are in various colors, can do that (1 level of 
    recursion; not necessary for older worlds since added in Minecraft 
    Java Edition 1.11 "The Exploration Update").
- oak wood stairs: (3, 64, 270) (big end pointing North).
- upside-down oak wood stairs: (3, 63, 270) (big end pointing South).
- A dragon egg (node) is at (19, 69, 261).
- A chest at (19, 69, 262) contains: dragon egg
- A dispenser at (18, 69, 273) contains: (16) arrow
- A "carpetlike" snow pad is at (24, 70, 264)
- A full snow block (1x1x1) is at (24, 69, 264).
- ender chest: (15, 68, 252)
- stairs form a seemless square from SW corner stairs at (4, 68, 246) from NE corner stairs at (6, 68, 244)
- obsidian: (24, 69, 265)

### Items in World for MineClone2
The following nodes are not relevant to Minetest (are dispensiable), 
but are relevant to MineClone2.
- An end portal frame ("End Portal") without an eye of ender is at
  (20, 69, 257), one with an eye is at (23, 69, 256) and part of the starry teleportation square the ones with eyes generate is at (24, 69, 256).
- nether wart (full grown?) is at (17, 68, 264)
  - [ ] add one to a chest
- soul sand is at (17, 67, 264)

#### Rails
At (10, 68, 253) is a rail that behaves as a switch rail. The "source"
rail (from which the cart arrives) is at (9, 68, 253), so the switch
rail is East of it. When the lever at (11, 68, 253) is on, the switch and rail point
toward the North (left).

### entities
- All carts can either be discarded or converted to a regular cart. Preserving the inventory of a Minecart with Chest is ideal, but people usually don't store anything important in there as it is for transportation.
- a Minecart is at (7, 68, 264)
- a Minecart with Hopper is at (1, 68, 253)

