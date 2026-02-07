# 🎮 Trimui Smart Pro & CrossMix OS – Complete Guide

This repository is a **practical, opinionated, real-world guide** for people using
the **TrimUI Smart Pro**, with a focus on **CrossMix OS**.
---

## 🎯 Who is this repository for?

- Anyone who just bought a **Trimui Smart Pro**
- Users of **CrossMix OS** (or those planning to use it)
- People who prefer to **configure things properly** before playing
- Handheld, retro, and custom firmware enthusiasts
- Anyone who wants to understand *why something works (or doesn’t)*

---

## 🚫 What this repository does NOT contain

- ❌ ROMs
- ❌ Proprietary BIOS files
- ❌ Illegal or copyrighted content

This repository provides:
- ✅ Structure
- ✅ Configurations
- ✅ Best practices
- ✅ Clear documentation

ROMs and BIOS files are the user’s responsibility.

---

## 📦 What you’ll find here

- ⚙️ Recommended **per-emulator configurations**
- 🎮 **Per-game tweaks** (per-game configs)
- 💾 Save and save-state organization
- 🔋 Performance and battery tweaks
- 🎨 Visual adjustments that don’t kill performance
- 🚀 Practical **PortMaster** guide
- 🧩 Physical accessory recommendations
- 🧠 Day-to-day usage notes

---

## 🗂 Repository structure

```txt
crossmix/
  ├─ emulators/
  │   ├─ saves-states/
  │   │   ├─ gba/
  │   │   ├─ snes/
  │   │   └─ ps1/
  │   ├─ configs/
  │   │   ├─ gba.md
  │   │   ├─ snes.md
  │   │   └─ ps1.md
  │   └─ per-game/
  │       ├─ gba/
  │       ├─ snes/
  │       └─ ps1/
  │
  ├─ themes/
  │   ├─ recommended.md
  │
  ├─ portmaster/
  │   ├─ README.md
  │   ├─ recommended.md
  │   ├─ problematic.md
  │   └─ tweaks.md
  │
  └─ performance-tweaks.md
```

---

## 💾 Saves in CrossMix OS

Saves are stored on the **SD card**, usually **organized by emulator**.

### Normal saves

Most common path:
```
/roms/<EMULATOR>/saves/
```

Examples:
- `/roms/PS/.pcsx_rearmed_libretro`
- `/roms/SFC/.snes9x_libretro/Super Mario World.3.state`

The save file name usually **matches the ROM name**.

---

## 🎯 Per-Game Configurations

Not every game behaves well with the same settings.

This repository includes tweaks for games that:
- Suffer from FPS drops
- Have audio stuttering
- Need occasional frameskip
- Run better without shaders

Structure:
```
crossmix/emulators/per-game/<emulator>/<game>.md
```

Each file explains **why** each tweak exists.

---

## 🎨 Visuals and interface

Focus areas:
- Themes compatible with CrossMix OS
- Good readability on the TrimUI screen
- Brightness and contrast adjustments
- Lightweight, useful shaders

No aesthetics that sacrifice battery life.

---

## 🚀 PortMaster

PortMaster works, but it’s **not plug-and-play**.

Here you’ll find:
- Ports that run well
- Ports that need tweaks
- Ports that aren’t worth the effort
- Documented common issues

---

## 🧩 Physical accessories

Recommendations based on real usage:
- Reliable SD cards
- Proper cases and sleeves
- Screen protectors (when worth it)
- Useful cables and adapters
- What’s not worth buying

---

## 🤝 Contributions

Suggestions are welcome, especially:
- Game recommendations
- Tested configurations
- Per-game tweaks
- Performance improvements
- Documentation fixes
- Real-world experiences
---