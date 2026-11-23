# UniversalTurretAmmo — Project Handoff

> **Last Updated**: 2026-11-23  
> **Global Context**: [../../rbnd.cc/AGENTS.md](../../rbnd.cc/AGENTS.md)

## Current State
- **Version 2.2** released with full **Vortex Mod Manager (FOMOD)** support.
- Added [fomod/info.xml](file:///c:/Users/Myke/Documents/GitHub/UniversalTurretAmmo/fomod/info.xml) and [fomod/ModuleConfig.xml](file:///c:/Users/Myke/Documents/GitHub/UniversalTurretAmmo/fomod/ModuleConfig.xml) so Vortex presents a variant selector (**Standard** vs **Ballistics-Only**) during installation and deploys `ModInfo.xml`, `README.md`, and the selected `Config/` folder directly to the mod root.
- Updated [UniversalTurretAmmo/ModInfo.xml](file:///c:/Users/Myke/Documents/GitHub/UniversalTurretAmmo/UniversalTurretAmmo/ModInfo.xml) and [README.md](file:///c:/Users/Myke/Documents/GitHub/UniversalTurretAmmo/README.md) to `2.2` and rebuilt [UniversalTurretAmmo.zip](file:///c:/Users/Myke/Documents/GitHub/UniversalTurretAmmo/UniversalTurretAmmo.zip).
- Verified all XML files parse cleanly.

## Next Steps
- Drag-and-drop [UniversalTurretAmmo.zip](file:///c:/Users/Myke/Documents/GitHub/UniversalTurretAmmo/UniversalTurretAmmo.zip) into Vortex (and remove the manual `UniversalTurretAmmo` folder from `%APPDATA%\7DaysToDie\Mods` if still present) to test the FOMOD prompt end-to-end.
