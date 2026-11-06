# Ashfall Modpack

A zombie-survival modpack for Minecraft 26.3 (Fabric). Scavenge a dead city, arm up, reclaim it one district at a time and turn the power back on.

**Install:** download the newest `.mrpack` below and import it into Prism Launcher or the Modrinth App. The player guide is in this repo's [wiki](../../wiki).

## Releases

Newest first. The version is MAJOR.MEDIUM.MINOR: major for a new core system, medium for new features or a world-generation change, minor for fixes and tweaks.

### 10.2.2: Balance fixes (`Ashfall-10.2.2.mrpack`)
**Changed**
- **Storm Repeater:** fires 400 a minute (was 600) and uses 2 energy and 7 heat per shot, so it no longer beats every other gun at everything. The Lancer cools faster.
- **Overcharger:** adds less heat (×1.2, was ×1.4), so it's no longer a downgrade.
- **Pipe Wrench:** swings faster, a real alternative to the Machete.
- **Energy Cell:** costs 4 Wire Spools and a Battery (was 8 spools).
- **Guards:** deal a player's damage per hit and have 30 health, so they can hold their own against walkers.
- **Mechanics:** repair one step of wear every 30 s instead of fully restoring a block, so walls under attack can still fall.
- **Scavengers:** keep only a quarter of the Antibiotics they find.
- **Repairs:** each one takes off 45 wear, with a 1 s cooldown between repairs. Wood takes a plank and 2 Nails, and obsidian takes Scrap Metal instead of cobblestone. Worn-out iron and Reinforced doors no longer drop scrap.

**Fixed**
- The guide's horde-tier days and the zombie-cap text ("day 120") now match the game.

### 10.2.1: Polished Arms (`Ashfall-10.2.1.mrpack`)
**Added**
- **Ashfall Polished Arms:** an optional resource pack that repaints these as dark machined gunmetal at twice the texture detail:
  - the seven blasters;
  - both Plasma Blades;
  - the Flamethrower;
  - the Arc Charge.

  Knurled rubber grips, screws and sharp highlights replace the rust and duct tape. Each weapon keeps its shape, glow colour and stats. Turn it on in **Options → Resource Packs**; it's off by default.

### 10.2.0: Block wear, the Arc Charge and a friendly fire switch (`Ashfall-10.2.0.mrpack`)
**Added**
- **Block wear:** zombies now wear down fortified blocks (Reinforced Planks, Barricades, reinforced, iron and copper doors, iron bars, iron blocks, obsidian). A horde on one spot gets through in seconds to a minute.
  - A worn-out block gives way to a weaker one: Reinforced Planks become oak planks, doors and Barricades break, iron and obsidian become cobblestone.
  - Cracks show the wear, and Jade shows it as "Worn 40%".
  - **Repairs:** right-click a worn block with Scrap Metal (metal), a plank and Nails (wood) or cobblestone (obsidian) to take some wear off.
  - Mechanic survivors repair worn blocks in their claim from the Supply Lockers.
  - After a horde night, the Bunker Core warns you at dawn if blocks in its claim are badly worn.
  - Wear stays on a block when you break and re-place it, or push it with a piston.
- **Arc Charge:** a thrown stun grenade (Battery, Scrap Electronics and Duct Tape make 2). One second after it sticks, it stuns every hostile mob it can see within 5 blocks for 3 s. It does no damage, but the bang carries 32 blocks. It's also found in police stations, supply drops and Strongboxes.
- **Friendly fire switch:** a new **Friendly fire** game rule, off by default (a button in the Game Rules screen, or `/gamerule ashfall:friendly_fire true`). With it on, players can hurt pets, the Flamethrower burns other players and Arc Charges stun pets. Survivors stay protected either way.

**Changed**
- Fortified blocks are no longer unbreakable to zombies, so bases need upkeep.
- Survivors refuse bottled water and golden apples as food, and ignore lava, fire, suffocation and falling blocks.
- Rescues skip players whose group is full, and rescues and holdouts say when the world has no room for more survivors.
- Medics treat only their own group.
- Carry On can no longer pick up Supply Lockers.

**Fixed**
- A horde wave that only partly spawned lost the rest of its zombies. They now still spawn.
- Some graffiti marks dropped out of the map index.

### 10.1.0: Weapon handling, stun mode and the Flamethrower (`Ashfall-10.1.0.mrpack`)
**Added**
- **Weapon weight:** the weapon in your hand slows you, from −3% for pistols and light melee to −15% for the Storm Repeater and Flamethrower.
- **Draw time:** blasters and the Flamethrower take 0.3–0.9 s to draw before they can fire, with a READYING bar on the HUD. Melee weapons stay instant.
- **Stun mode:** the Spark Pistol, Volt Sidearm and Ion Rifle switch between damage and stun with **C**. A stun shot freezes a zombie for 3 s, deals no damage, makes no noise and costs 3× the energy.
- **Flamethrower:** refuel with Lighter Fluid using the reload key. It sets crowds of zombies alight, makes noise zombies hear from 24 blocks, and never sets blocks on fire or hurts pets, survivors or players.

**Changed**
- Zombies attack whoever is nearest, a player or a survivor, so survivors following you can be bitten.
- You can't reload while a blaster is drawing or between semi-auto shots.
- Carry On can only pick up containers: chests, barrels, shulker boxes and Supply Lockers.

**Removed**
- Picking up mobs, players and other blocks with Carry On.

### 10.0.0: Survivors (`Ashfall-10.0.0.mrpack`)
**Added**
- Survivors: living NPCs you can find, recruit and settle at your Bunker Core.
  - **Finding them:** from day 7, finished distress radio calls leave a survivor, and a few buildings hide one on an upper floor who calls out when you come near.
  - **Orders:** right-click a survivor for buttons: Follow, Stay, Settle here, Home, or a job.
  - **Jobs:**
    - **Guard:** fights zombies with a melee weapon you hand them.
    - **Scavenger:** goes out once a day and brings back loot.
    - **Medic:** bandages people and cures bitten survivors.
    - **Mechanic:** repairs spike strips and relays.
  - **Supply Locker:** a new block in your base's claim. Survivors take their supplies and daily food only from Supply Lockers. A day's food is 5 hunger points, about one loaf of bread; rotten flesh is refused.
  - **Changing jobs:** a survivor works at half speed on their first day in a new job, and can't change jobs on horde nights.
  - **Danger:** zombies hunt survivors, and a bitten survivor turns unless given Antibiotics. Players can't hurt survivors.
  - **Limits:** 6 survivors per group or base, 30 per world.
- Traders: reclaimed districts get a Trader at their substation, with their own stock that refills every 3 days.

### 9.12.0: Graffiti, dogs, keys and safes (`Ashfall-9.12.0.mrpack`)
**Added**
- **Spray Can:** paints Cleared, Danger, Loot, Safehouse and arrow marks on walls. Cleared marks warn you if zombies are still inside and go stale when the building refills. Marks show on the Grid Map for your party.
- **Dogs:**
  - Stray Dogs appear in residential areas and tame with rotten flesh or a bone.
  - Tamed dogs quietly warn their owner of nearby zombies, bite zombies for 2 damage, and come along on fast travel.
  - Nothing a player does can hurt a pet.
- **Strongboxes:** safes with better loot in some of the better buildings. One of that building's zombies carries the key, or you can force the box with a noisy Crowbar.

**Changed**
- Weapon Parts are slightly more common in police stations, workshops and town halls.

### 9.11.0: Radio jobs, traps and lures (`Ashfall-9.11.0.mrpack`)
**Added**
- **Shortwave Set:** picks up timed jobs aimed at real buildings: find a stash, clear a nest, or hold a distress beacon. Rewards grow with district danger.
- **Traps and lures:** Rattle Box (a wind-up noise lure), Tripline Alarm (warns you when zombies pass) and Spike Strip (slows and hurts zombies, wears out).

**Fixed**
- Horde nights: a wave that couldn't find a place to spawn was lost, so some horde nights had no zombies at all. Waves now retry until they spawn.

### 9.10.0: Random police stations (`Ashfall-9.10.0.mrpack`)
**Changed**
- Police stations now generate randomly in every district except the wasteland. Only the Downtown station has the armory cache.
- This changes world generation: in worlds made with earlier versions, newly explored areas will generate differently.
- Versions are now numbered MAJOR.MEDIUM.MINOR. Under the new scheme, 1.0.0-rc15 is 9.9.1.

### 1.0.0-rc15 (9.9.1): Balance tweaks (`Ashfall-1.0.0-rc15.mrpack`)
**Changed**
- Bandages work like food: eating animation, 1.6 seconds to use.
- The bicycle is slower, about 11 blocks a second.
- Grid Couplers take 1 Weapon Part plus Scrap Metal.
- Weapon Parts are more common in workshops, police stations, town halls and supply drops.

**Removed**
- The "Not usable yet" tooltip.

### 1.0.0-rc14 (9.9.0): Quiet weapons (`Ashfall-1.0.0-rc14.mrpack`)
**Added**
- Melee weapons that make no noise: Pipe Wrench, Scrap Machete and Rebar Spear.
- Nail Launcher and Nails: a quiet ranged weapon.
- Bottle Lure: throw it to make a noise where it lands and pull zombies away.
- Nails and worn wrenches can be found in workshops.
