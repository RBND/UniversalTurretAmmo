# Universal Turret Ammo (v2.1)

**This mod allows your automated base defense turrets in 7 Days to Die to use additional compatible ammunition types instead of being restricted to base ammunition.**

Ammunition types **dynamically affect stats** (damage, penetration, armor piercing, range, and pellet count) on a **per-shot basis** as ammo is consumed.

---

### Supported Turrets & Dynamic Ammunition Stats

#### SMG Auto Turret
| Ammo Type | Entity Damage | Block Damage | Target Armor | Penetration | Range / Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **9mm Ball** | 32 | 6 | Standard | 0 | Standard 9mm round |
| **9mm HP** | 35 | 7 | Standard | 0 | +Hollow point flesh damage |
| **9mm AP** | 38 | 8 | -50% Armor | 0 | Armor piercing |
| **.44 Magnum Ball** | 70 | 12 | Standard | 0 | Heavy magnum punch |
| **.44 Magnum HP** | 77 | 13 | Standard | 0 | Heavy hollow point damage |
| **.44 Magnum AP** | 84 | 14 | -50% Armor | 1 Zombie | Heavy armor piercing + penetration |
| **Robotic Turret Ammo** | 11.8 | 1 | Standard | 0 | High-capacity backup ammo |
| **Robotic Turret AP Ammo** | 14.1 | 1 | -50% Armor | 1 Zombie | High-capacity AP ammo |

#### Shotgun Auto Turret
| Ammo Type | Entity Damage | Block Damage | Ray Count | Penetration | Range / Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Shotgun Shells** | ~10 / pellet | 5.4 | 8 pellets | 0 | Standard buckshot cone |
| **Shotgun AP Slugs** | 175 | 80 | 1 heavy slug | 1 Zombie | 18m effective range |
| **Shotgun Breaching Slugs**| 96 | 80 (+1000 doors) | 1 slug | 0 | Anti-door / heavy block damage |
| **Robotic Turret Shells** | 2.1 / pellet | 0 | 8 pellets | 1 Zombie | 15m range, zombie penetration |

#### M60 Auto Turret
| Ammo Type | Entity Damage | Block Damage | Target Armor | Penetration | Range / Notes |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **7.62mm Ball** | 47 | 8 | Standard | 0 | Standard battle rifle round |
| **7.62mm HP** | 52 | 9 | Standard | 0 | Heavy hollow point damage |
| **7.62mm AP** | 57 | 10 | -50% Armor | 1 Zombie | Armor piercing + penetration |
| **Robotic Turret Ammo** | 11.8 | 1 | Standard | 0 | High-capacity backup ammo |
| **Robotic Turret AP Ammo** | 14.1 | 1 | -50% Armor | 1 Zombie | High-capacity AP ammo |

---

### How Dynamic Stat Switching Works
When you load multiple ammo stacks into a turret (e.g. .44 Magnum in slot 1 and 9mm in slot 2):
1. The turret feeds from left-to-right.
2. While firing from slot 1, every shot uses the full damage, penetration, and armor-piercing stats of that specific ammunition.
3. As soon as slot 1 empties, the turret immediately and seamlessly adapts to the stats of the ammunition in slot 2 without interruption.

---

### Optional Variants
If you prefer not to allow Robotic Turret ammunition in powered base turrets, a **Ballistics-Only** configuration is provided in the `Optional_Variants/Ballistics-Only/` folder:
- **Ballistics-Only**: Allows .44 Magnum in SMG turrets alongside 9mm, but excludes all Robotic Turret ammo from SMG, Shotgun, and M60 turrets.

To use an optional variant:
1. Copy `blocks.xml` from `Optional_Variants/Ballistics-Only/Config/`.
2. Replace `UniversalTurretAmmo/Config/blocks.xml` with it.

---

### Installation

#### Single Player / Local Game
1. Download or clone this repository.
2. Place the `UniversalTurretAmmo` folder into your game's **Mods** directory:
   - Steam default path:  
     `C:\Program Files (x86)\Steam\steamapps\common\7 Days To Die\Mods`
   - *(If the `Mods` folder does not exist, create it).*
3. Launch the game and enjoy!

#### Dedicated Server
1. Stop your server if it is running.
2. Place the `UniversalTurretAmmo` folder into your server's **Mods** directory:
   - Example (SteamCMD install):  
     `C:\7DaysToDieServer\Mods`
   - Linux default:  
     `/home/steam/7dtd/Mods`
3. Restart your server — the mod will load automatically.
