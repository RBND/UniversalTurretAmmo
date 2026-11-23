# UniversalTurretAmmo — Project Guidelines & Context

> **Global Context & Secret Rules**: Always read [../rbnd.cc/AGENTS.md](../rbnd.cc/AGENTS.md) and [./.context/handoff.md](./.context/handoff.md) first, and update ./.context/handoff.md when finished.

## 1. Tech Stack & Target Host
- **Project**: UniversalTurretAmmo
- **Primary Stack**: DayZ Mod Config & Scripts
- **Target Host**: Z790

## 2. Build / Run Commands
`powershell
DayZ Addon Builder
`

## 3. Core Rules
1. Never hardcode or print raw secret values; use .env.tpl and op run --env-file=".env.tpl" -- <cmd> (see ../rbnd.cc/context/secrets-catalog.md).
2. Record architectural decisions in .context/decisions.md and update .context/handoff.md instead of creating scattered markdown files.
3. Always increment the version number and commit and push to GitHub when finishing code modifications.
