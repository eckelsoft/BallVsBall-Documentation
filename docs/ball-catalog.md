# Ball catalog

See the balls at a glance and how their current abilities work. The numbers come from the live Verse catalog and ability descriptions in the game project; they describe this implementation and can change with balance updates.

There are **25 standard balls**. The **Pumpkin Ball** becomes available to a player after ten hours of playtime, for **26 available balls**. In single-player, the computer may also draw the Pumpkin Ball before the player unlocks it. The retired Legacy Poison entry is not selectable.

| Ball | Icon | Current ability |
|---|:---:|---|
| **Verity** | <img src="../assets/balls/verity.png" alt="Verity ball" width="56"> | Taking a hit has a 19% chance to trigger 10 seconds of Rage. Rage increases size by 38% and contact damage to 40. Triggers have a 4–6 second cooldown. |
| **Blade** | <img src="../assets/balls/blade.png" alt="Blade ball" width="56"> | Starts with one orbiting blade and gains another every 4 seconds, up to five. Each blade deals 8 damage per pass. Hits do not remove blades. |
| **Frost** | <img src="../assets/balls/frost.png" alt="Frost ball" width="56"> | Leaves an ice trail for 2.75 seconds. Enemies touching it freeze for 1.8 seconds and take six ticks of 4 damage, 0.28 seconds apart. Trails do not stack; a 0.5 second freeze guard follows. |
| **Apple** | <img src="../assets/balls/apple.png" alt="Apple ball" width="56"> | Drops an apple behind itself every 1.25 seconds. Allies heal 2 HP; enemies take 5 damage. Apples last 10 seconds, can be collected once, and are capped at 12 active. They disappear when their owner is knocked out. |
| **Cactus** | <img src="../assets/balls/cactus.png" alt="Cactus ball" width="56"> | Plants three cacti after 4 seconds, then every 5 seconds. Enemy contact deals 6 damage and bounces them; allies pass through. Cacti last 5.5 seconds. |
| **Cell Ball** | <img src="../assets/balls/cell.png" alt="Cell ball" width="56"> | Starts at 30 HP and grows after 1.8 seconds without a hit, up to 40 HP. A hit that leaves it alive at 32 HP or more splits its remaining HP between two cells. Cells share 4.4 HP/s healing, with a team cap of 8 cells and 100 HP. |
| **Bomb** | <img src="../assets/balls/bomb.png" alt="Bomb ball" width="56"> | Drops a bomb every 1.25 seconds. It explodes after 4 seconds, dealing 15 damage and knockback. Each blast hits each enemy once; allies are safe. |
| **Spider** | <img src="../assets/balls/spider.png" alt="Spider ball" width="56"> | Wall bounces leave threads attached to the spider. Enemies touching a thread slow down and take 1 damage per thread every 0.25 seconds. Up to 32 threads last until their owner is knocked out or the round ends. |
| **Shackle Ball** | <img src="../assets/balls/shackle.png" alt="Shackle ball" width="56"> | Creates three rings for 5.2 seconds every 7.5–10.5 seconds. Enemies fully entering a ring are trapped. Each bounce against its inner edge deals 4 damage. |
| **Harpoon** | <img src="../assets/balls/harpoon.png" alt="Harpoon ball" width="56"> | Fires a bouncing harpoon after 3 seconds and pulls a caught enemy back, dealing 2 damage every 0.12 seconds. The owner stops and stays vulnerable during the pull. Freeze, shackles, or knockout interrupt it; recovery takes 2.5 seconds. |
| **Laser** | <img src="../assets/balls/laser.png" alt="Laser ball" width="56"> | Wall bounces leave fixed lasers for 5 seconds, up to four active. Each deals 4 damage every 0.5 seconds to enemies in its core. The glow is cosmetic; owner knockout clears the lasers. |
| **Honeycomb** | <img src="../assets/balls/honeycomb.png" alt="Honeycomb ball" width="56"> | Sends three seeking bees after 2.5 seconds, then every 4 seconds. Each bee hits once for 2 damage and lasts up to 3 seconds. Up to six bees can be active; allies are safe. |
| **Virus** | <img src="../assets/balls/virus.png" alt="Virus ball" width="56"> | Contact infects an enemy for 4 seconds. The infection deals 1.5 damage every 0.75 seconds. Spores can apply or extend an infection, but infection ticks do not stack. |
| **Thief** | <img src="../assets/balls/thief.png" alt="Thief ball" width="56"> | Starts throwing knives after 1.5 seconds, then every 2 seconds. Each knife deals 3 damage. At 80/60/40/20 HP it throws 2/3/4/5 knives; healing lowers the count. Each knife can hit once. |
| **Poison Thorn** | <img src="../assets/balls/poison-thorn.png" alt="Poison Thorn ball" width="56"> | Grows three thorns on each wall after 3 seconds, then every 7.5 seconds. Thorns last 6 seconds. Contact deals 2 damage plus 2 seconds of poison at 1.05 damage/s. Each thorn can hit the same enemy every 0.65 seconds. |
| **Electro** | <img src="../assets/balls/electro.png" alt="Electro ball" width="56"> | Fires lightning after 1.6 seconds, then every 3.6 seconds for 6 damage. It chains to one nearby enemy for 3 damage. Contact adds 3 damage and a 0.75 second stop, once per target every 1.6 seconds. |
| **Acid Ball** | <img src="../assets/balls/acid.png" alt="Acid ball" width="56"> | Fires every 3.2 seconds for 3.15 damage and leaves a puddle for 4 seconds. Puddles deal 2.1 contact damage and burn for 3 seconds at 1.05 damage every 0.75 seconds. Burns continue outside the puddle and do not stack. |
| **Range** | <img src="../assets/balls/range.png" alt="Range ball" width="56"> | Sends an expanding wave every 4.5 seconds. The edge deals 6 damage once to each enemy as it passes; the wave expands for 0.95 seconds. |
| **Snake** | <img src="../assets/balls/snake.png" alt="Snake ball" width="56"> | Grows a tail link every 1.6 seconds, up to five links. Links deal 3–10 damage and knock enemies back; the tip hits hardest. An enemy can take one tail hit every 0.8 seconds. |
| **Minigun** | <img src="../assets/balls/minigun.png" alt="Minigun ball" width="56"> | Fires at the nearest enemy every 0.30 seconds for 1 damage. Dealing or taking a hit pauses firing for 0.35 seconds. Shots have no spread or leading; the first shot comes after 1 second. |
| **Shotgun** | <img src="../assets/balls/shotgun.png" alt="Shotgun ball" width="56"> | Fires seven shots in a spread, each dealing 4 damage on hit. After 8 seconds without taking a hit it fires a second volley 0.24 seconds later. First volley: 3.5–6 seconds; later volleys: 4.2–7.2 seconds. |
| **Axe** | <img src="../assets/balls/axe.png" alt="Axe ball" width="56"> | Starts with 120 HP and a spinning axe. Lower HP makes it spin faster and deal more damage, from 4 to 12. Only the blade hits; freeze and pull stop its rotation. |
| **Glass Ball** | <img src="../assets/balls/glass.png" alt="Glass ball" width="56"> | Wall bounces and incoming hits create glass shards. Each shard deals 4 damage to an enemy, then breaks. Up to 32 shards remain until owner knockout or round end. |
| **Beam Ball** | <img src="../assets/balls/beam.png" alt="Beam ball" width="56"> | Charges for 2.5 seconds, then fires for 2 seconds with limited turning speed. The first enemy in its 680 cm beam takes 3 damage every 0.25 seconds. It recharges for 3.75 seconds. |
| **Vampire Ball** | <img src="../assets/balls/vampire.png" alt="Vampire ball" width="56"> | Latches onto an enemy for 2 seconds while it keeps moving. Every 0.5 seconds it deals 4 damage and heals the same amount, up to 120 HP. Freeze, shackles, pull, or a blocked position break the latch. |
| **Pumpkin Ball** · unlockable | <img src="../assets/balls/pumpkin.png" alt="Pumpkin ball" width="56"> | Unlock after 10 hours of playtime. Leaves a pot every 0.7 seconds, up to three active; each lasts 8 seconds, deals 6 damage on contact, and drops candy every 0.7 seconds. Each pot drops up to three candies per wave, then starts a new wave after all of its candies are collected or expire. Each candy deals 4 damage once and lasts 5 seconds. All effects clear on owner knockout. |

## Availability notes

- The Pumpkin Ball is a playtime reward for players. It is included in the computer opponent's pool in single-player, even before the player unlocks it.
- The old poison ID remains in the code for saved-data compatibility. It is unavailable and not a ball in the selectable catalog. Virus and Poison Thorn are separate, available balls.
- Icon PNGs in this repository are direct exports of the corresponding UEFN textures. Unreal asset files stay in the game project.

## Updating this page

Check the Verse catalog, current gameplay constants, and the player-facing ability descriptions before changing an entry. Keep the icon, name, unlock status, and ability values in sync. Record the game revision or verification date in the commit message.
