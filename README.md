# Modded APKs — Reverse Engineering Experiments

> **Purpose:** This gist is for keeping and documenting my reverse-engineering / APK modding experiments. Each project is a real, working mod I successfully built. This is a learning log — progress, methods, and outcomes.

**Important:** All mods are for personal research and education only. I do not distribute or sell them.

---

## Project Table

| # | App | Version | Package | Mod Description | Method Used | Status | Download |
|---|-----|---------|---------|-----------------|-------------|--------|----------|
| 1 | AdGuard | 4.12.81 | `com.adguard.android` | Force all license/premium features active (tracking protection, browsing security) without a paid license; license screen shows premium | Smali patch + rebuild via apktool + re-sign | ✅ Done | [Release](https://github.com/MaheshSharan/Modded-APKs/releases/tag/Adguard) |
| 2 | JioSaavn | 10.9.2 | `com.jio.media.jiobeats` | Unlocked permanent Pro subscription privileges (320 kbps Extreme HD audio stream, ad-free playback, unlimited skips, Pro UI header badge), neutralized proprietary divide-by-zero & 677MB OOM anti-tamper traps, merged multi-splits with 1:1 stock binary ARSC icon table into a single standalone APK | Smali state-machine patch + global reflection cert spoofing + binary `resources.arsc` chunk extraction + standalone monolithic APK repackaging | ✅ Done | [Release](https://github.com/MaheshSharan/Modded-APKs/releases/tag/JioSaavn) |

---

### Notes / Status Legend
- ✅ Done — working, verified
- 🚧 In progress
- 🔜 Planned

---
More projects will be added to the table as I complete them.
