# UniversalTurretAmmo — Architectural Decisions

## 2026-11-02: Standardized Context & 1Password CLI Architecture
- Adopted two-tier context hierarchy anchored in C:\Users\Myke\Documents\GitHub\rbnd.cc.
- Enforced zero-plaintext credential rule using 1Password CLI (op:// secret references).

## 2026-11-23: FOMOD Packaging for Vortex Compatibility (v2.2)
- Chose a single-archive FOMOD installer (`fomod/info.xml` and `fomod/ModuleConfig.xml`) over dual release ZIPs so Vortex users can select between Standard and Ballistics-Only during installation while preserving the manual folder layout.
