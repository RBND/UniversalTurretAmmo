# Universal Turret Ammo (v2.0)

**This mod allows your automated base defense turrets in 7 Days to Die to use additional compatible ammunition types instead of being restricted to base ammunition.**

---

### Supported Turrets & Ammunition

#### SMG Auto Turret
- **9mm Rounds**: Standard (Ball), Armor Piercing (AP), Hollow Point (HP)
- **.44 Magnum Rounds**: Standard (Ball), Armor Piercing (AP), Hollow Point (HP)
- **Robotic Turret Ammo**: Regular and Armor Piercing (AP)

#### Shotgun Auto Turret
- **Shotgun Rounds**: Standard Shells, AP Slugs, Breaching Slugs
- **Robotic Turret Shells**

#### M60 Auto Turret
- **7.62mm Rounds**: Standard (Ball), Armor Piercing (AP), Hollow Point (HP)
- **Robotic Turret Ammo**: Regular and Armor Piercing (AP)

---

### Mechanics & Stats Note
*This mod updates the accepted ammo definitions for each turret. In 7 Days to Die, base turret firing rate, cone spread, and damage calculations remain governed by the respective turret block properties.*

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
