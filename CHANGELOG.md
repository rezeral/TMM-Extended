# beta-2.2.126

### 🆕 Additions
- New roles:
  - Mimic
    - Civilian Role
    - Appears as a Killer Cohort to other killers
    - Spawns with a Fake Knife
    - Can purchase *Lockpicks*, *Delusion Vials*, *Firecrackers* and *Notes*
    - Gains coins passively over time.
  - Guesser *(Disabled by default)*
    - Civilian Role
    - Can guess player's role: if the guess is correct the player dies; if incorrect, the Guesser dies.
- Added blood particle effects when killing players *(Disabled by default, can be enabled/disabled using <kbd>B</kbd>)
- Added some little QoL mods
- Added a cinematic intro at launch (might be buggy but I though it would look cool so I made it :3)
- New overhauled main menu layout
- New modpack icon, thumbnail and backgrounds

### 📋 Changes
- Gameplay balancing:
  - **Conductor**
    - The *Master Key* will now be seen as a *Lockpick* for others if there's less than 10 players in the game.
  - **Voodoo**
    - Shooting the Voodoo now causes revolvers to drop from the shooter.
  - Disabled the backfire mechanic
- Game auto-start timer is now 30 seconds instead of 10.
- Items that falls outside the train (in the void) will now be teleported back to the closest dead body.

### 🔧 Fixes
- Players won't take fall damage and fire damage anymore
- Fixed the fast teleportation item not being given to players that've joined late
- Fixed knockback not being applied when punching with a *Knife*
- Fixed missplaced interaction safeguards (should be fully fixed now!)

> ### Planned
> - Random player teleportation table at the start of each game *(Probably comming in the next update)*
> - Admin/OP configuration menu for TMM
> - Add more detailed train decorations and furniture
> - Expand and enhance scenery & lobby
> - ~~New tasks~~ *(Waiting for a good way to implement such thing as an add-on to TMM)*

# beta-2.1.126

### 🔧 Fixes
- Fixed outdated mod configurations, should be better now for people updating the modpack if it was already installed (sorry)

# beta-2.0.126

### 🆕 Additions
- New roles:
  - **Vulture**
    - Neutral Role
    - Can eat dead bodies to turn into a killer
    - Only enables past 8 players.
  - **Recaller**
    - Civilian Role
    - Can save a location to teleport to later from 100 coins.
    - Gains 50 coins per task done.
  - **Better Vigilante** *(Disabled by default)*
    - Civilian Role
    - Spawns with a revolver and a grenade
- New items:
  - **Defense Vial**
    - **Bartender** exclusive
    - Grants the drinker one extra hit (similar to Psycho Armor).
  - **Delusion Vial**
    - **Jester** exclusive
    - Mimics poison by applying visual effects but does not cause death.
- Added an item that fast teleports you to the Lobby train
- Added a system preventing players from standing close/inside train doors before the game starts (wich was allowing them to exit the train without needing a Master Key, Lockpick, or Crowbar).

### 📋 Changes
- Gameplay balancing:
  - **Bartender**
    - Can see poison and poisoned players.
    - Can now purchase a *Defense Vial* for 100 coins (50 coins per task).
  - **Jester**
    - Can now see the round timer.
    - Can shoot with their fake gun.
    - Gains coins passively over time.
    - Can purchase *Firecrackers*, *Lockpicks*, *Notes*, and *Delusion Vials*.
  - **Coroner**
    - Can see the roles of dead players (also visible to spectators).
  - **Executionner**
    - Gains coins passively over time.
    - Can purchase *Firecrackers*, *Lockpicks*, *Notes*, and *Delusion Vials*.
    - Their target's skin can now be seen on the UI
  - **Noisemaker**
    - Gains coins passively over time.
    - Can purchase *Firecrackers* for 75 coins.
  - When innocents shoots other innoncents, assuming they've passed the backfire chance, they drop their gun and won't be able to pick one up until the end of the game
- **Phantom** is now enabled by default.
- **Executioner** is now enabled by default.
- The **Executioner**'s targets are now visible to spectators when hovering over the **Executioner**.

### 🔧 Fixes
- Some HUD/Menus fixes
- Removed Fresh Moves (With animated eyes) due to compatibility issues
- Removed Essential mod due to compatibility issues, can be added back if wanted but might break some stuff.
- Interaction safeguards are now fully completed, no more glitch abuses with trapdoors and other stuff!
- Fixed the ready-area boundaries.

# alpha-1.6.126

### 🆕 Additions
- Added Noelle's Roles add-on for TMM (see the description for more informations about the roles)
- Added default mod configuration (in case some people want to change client-side settings)

### 🔧 Fixes
- Some HUD/Menus tweaks and fixes
- Various map fixes
- *...and maybe some more stuff that I've forgot*

# alpha-1.5.126

### 🆕 Additions
- Added interaction safeguards to the lobby and within the playable train **(WIP)**

### 📋 Changes
- Removed unneeded modded items and blocks
- Adjusted shader settings to reduce blurriness and improve brightness **(WIP, still experiencing notable lag)**

### 🔧 Fixes
- Further reorganized and polished the train’s furniture and overall layout
- Minor tweaks to various mod configurations

# alpha-1.4.126

### 📋 Changes
- Removed unneeded mods

### 🔧 Fixes
- Fixed collisions, they should be working correctly now
- Room key assignments fixed (for real this time)

# alpha-1.3.126

### 📋 Changes
- Harpy Express mod updated to the latest release

### 🔧 Fixes
- Room keys assignment fixed
- Missing blocks and furniture models fixed
- Various HUD tweaks and fixes

# alpha-1.2.115

### 🆕 Additions
- Fully revamped HUD and menu elements with new themes and visual styles
- Added a default client configuration
- Added Shader configuration (WIP, shaders currently cause significant lag)
- Updated the world save file with a refined lobby and ongoing train customization (WIP)
- Complete client and mod configurations

### 🔧 Fixes
- Various performance optimizations
