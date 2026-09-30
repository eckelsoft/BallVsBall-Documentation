# BallVsBall — Ball catalog

Verified snapshot of the **25 selectable balls** in the UEFN Verse catalog. Names, icon identifiers, and ability values below are transcribed from `Content/ball_probe_catalog.verse` and `Content/ball_probe_text.verse` in the game project. This is documentation, not yet the source of truth; the live Verse implementation remains authoritative. Recheck this page after gameplay or balance changes.

> **Artwork:** the `Icon asset` column names the existing UEFN texture. No Unreal `.uasset` files have been copied into this repository. Add an approved PNG export under `../assets/balls/` before replacing “pending” with an image embed. This avoids duplicating binary assets or implying they are ready for distribution.

| Ball | Icon asset (UEFN) | Ability and current documented values | Image |
|---|---|---|---|
| Verity | `T_ball_verity` | Hits have a 19% chance to trigger 10s of rage. Rage boosts size by 38% and contact damage to 40. Each trigger has a 4–6s cooldown. | Pending approved export |
| Blade | `T_ball_blade` | Starts with one orbiting blade; gains one every 4s, up to 5. Each blade deals 8 damage per pass. Taking damage does not remove blades. | Pending approved export |
| Frost | `T_ball_frost` | Leaves a fading ice trail for 3s. Enemies freeze for 2s and take 4 damage every 0.28s. Overlapping ice does not stack; 0.5s protection follows. | Pending approved export |
| Apple | `T_ball_apple` | Drops an apple every 1.25s. Allies heal 3 HP; enemies take 5. Each apple is collected once and lasts 10s, up to 12 active. Apples disappear when their owner is knocked out. | Pending approved export |
| Cactus | `T_ball_cactus` | Plants three cacti after 4s, then every 5s. Enemy contact deals 6 damage and causes a bounce. Allies pass through. Cacti last 5.5s. | Pending approved export |
| Cell Ball | `T_ball_cell` | Starts with 30 HP; heals up to 40 HP after 1.8s without a hit. A surviving hit at 32 HP or more splits the remaining HP between two cells. Cells share 4.4 HP/s of healing; up to 8 cells and 100 team HP. | Pending approved export |
| Bomb | `T_ball_bomb` | Drops a bomb every 1.25s. It explodes after 4s for 15 damage and knockback. Each blast hits each enemy once. Allies are safe. | Pending approved export |
| Spider | `T_ball_spider` | Each wall bounce leaves a thread attached to the spider. Touching enemies slow down and take 1 damage per thread every 0.25s. Up to 32 threads last until owner knockout or round end. | Pending approved export |
| Shackle Ball | `T_ball_cage` | Creates three rings for 5.2s, every 7.5–10.5s. Enemies that fully enter a ring are trapped inside. Each bounce against the inner edge deals 3 damage. | Pending approved export |
| Harpoon | `T_ball_harpoon` | Fires a bouncing harpoon after 3s and pulls a caught enemy back. The pull deals 2 damage every 0.12s. The owner stays still and vulnerable. Freeze, shackles or knockout interrupt it; recovery takes 2.5s. | Pending approved export |
| Laser | `T_ball_laser_violet` | Wall bounces leave fixed lasers for 5s, up to 4 active. Each laser deals 4 damage every 0.5s to enemies in its core. The glow does not hit. Owner knockout clears the lasers. | Pending approved export |
| Honeycomb | `T_ball_wabenball` | Sends three seeking bees after 2.5s, then every 4s. Each bee hits once for 2 damage and lasts up to 3s. Up to 6 bees can fly at once. Allies are safe. | Pending approved export |
| Virus | `T_ball_virus` | Contact infects enemies for 4s: 1.05 damage every 0.75s. Drops spores while an enemy is infected. Spores apply or extend infection; damage ticks do not stack. | Pending approved export |
| Thief | `T_ball_dieb` | Throws knives every 2s, starting after 1.5s; each deals 3 damage. At 80/60/40/20 HP, throws 2/3/4/5 knives instead of one. Healing reduces the count. Each knife hits once. | Pending approved export |
| Poison Thorn | `T_ball_giftstachel` | Three thorns grow on each wall after 3s, then every 7.5s. Thorns last 6s. Contact deals 2 damage plus 2s of poison (-1.05/s). Each thorn can hit an enemy every 0.65s. | Pending approved export |
| Electro | `T_ball_electro` | Fires lightning after 1.6s, then every 3.6s: 6 damage. Chains to one nearby enemy for 3 damage. Contact adds 3 damage and a 0.75s stop, once per target every 1.6s. | Pending approved export |
| Acid Ball | `T_ball_acid` | Fires every 3.2s for 3.15 damage and leaves a puddle for 4s. Puddles deal 2.1 contact damage and burn for 3s (-1.05 every 0.75s). Burn continues outside the puddle; overlapping burns do not stack. | Pending approved export |
| Range | `T_ball_range` | Sends out an expanding wave every 4.5s. Its edge deals 6 damage once per enemy. The wave expands for 0.95s. | Pending approved export |
| Snake | `T_ball_snake` | Grows one tail link every 1.6s, up to 5. Links deal 3–7 damage and knock enemies back; the tip hits hardest. Each enemy can take one tail hit every 0.8s. | Pending approved export |
| Minigun | `T_ball_minigun` | Fires at the nearest enemy every 0.30s for 1 damage. Dealing or taking a hit pauses firing for 0.35s. Shots have no spread or leading. First shot: 3.5–6s. | Pending approved export |
| Shotgun | `T_ball_shotgun` | Fires seven shots in a spread; each hit deals 4 damage. After 8s without taking a hit, fires a second volley 0.24s later. First volley: 3.5–6s. Next volleys: 4.2–7.2s. | Pending approved export |
| Axe | `T_ball_axe` | Starts with 120 HP and a spinning axe. Lower HP makes it spin faster and deal more damage (4–12). Only the blade hits. Freeze and pull stop its rotation. | Pending approved export |
| Glass Ball | `T_ball_glass` | Wall bounces and incoming hits create glass shards. Each shard deals 4 damage to an enemy, then breaks. Up to 32 shards remain until owner knockout or round end. | Pending approved export |
| Beam Ball | `T_icon_beam` | Charges for 2.5s, then fires for 2s with limited turning speed. Fast enemies can outrun its aim. The first enemy in the beam takes 3 damage every 0.25s. Range: 680 cm. Recharges for 3.75s. | Pending approved export |
| Vampire Ball | `T_icon_vampire` | Latches onto an enemy for 2s while it keeps moving. Every 0.5s, deals 4 damage and heals the same amount (up to 120 HP). Freeze, shackles, pull or a blocked position break the latch. | Pending approved export |

## Catalog notes

- The Verse enum also retains `Poison` as a **legacy, unavailable** entry (`Selectable := false`). It is not one of the 25 selectable balls and is intentionally omitted from the table. Virus and Poison Thorn are separate selectable abilities.
- The list order in the game catalog controls menu ordering; stable IDs are used for identity. Do not infer selectable order from the enum declaration.
- Values here describe the current localized probe catalog. They are not an independent balance approval and may not enumerate every runtime edge case.
- When updating: verify the current Verse implementation, update this snapshot and artwork references in the same change, and note the source revision/date in the commit.
