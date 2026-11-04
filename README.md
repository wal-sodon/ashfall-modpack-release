# Ashfall Modpack

A zombie-survival modpack for Minecraft 26.3 (Fabric). Scavenge a dead city, arm up, reclaim it one district at a time and turn the power back on.

**Install:** download the newest `.mrpack` below and import it into Prism Launcher or the Modrinth App. The player guide is in this repo's [wiki](../../wiki).

## Releases

Newest first. The version is MAJOR.MEDIUM.MINOR: major for a new core system, medium for new features or a world-generation change, minor for fixes and tweaks.

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
