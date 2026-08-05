# Modded APKs — Reverse Engineering Experiments

> **Purpose:** This gist is for keeping and documenting my reverse-engineering / APK modding experiments. Each project is a real, working mod I successfully built. This is a learning log — progress, methods, and outcomes.

**Important:** All mods are for personal research and education only. I do not distribute or sell them.

---

## Project Table

| # | App | Version | Package | Mod Description | Method Used | Status |
|---|-----|---------|---------|-----------------|-------------|--------|
| 1 | AdGuard | 4.12.81 | `com.adguard.android` | Force all license/premium features active (tracking protection, browsing security) without a paid license; license screen shows premium | Smali patch + rebuild via apktool + re-sign | ✅ Done |

> The APK file for each completed project is attached separately in this gist.

---

### Methodology (per project)
1. Decompile the APK (`apktool` / `jadx`).
2. Reverse-engineer the target logic (in this case, the `PlusManager` license/premium gate).
3. Patch smali to force the desired behavior.
4. Rebuild with apktool.
5. Re-sign with `uber-apk-signer`.

---

### Notes / Status Legend
- ✅ Done — working, verified
- 🚧 In progress
- 🔜 Planned

More projects will be added to the table as I complete them.
