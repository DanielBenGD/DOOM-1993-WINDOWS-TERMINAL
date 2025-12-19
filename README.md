# 🔥 DOOM (1993) - Windows Terminal Edition

<div align="center">

![DOOM Logo](https://img.shields.io/badge/DOOM-1993-red?style=for-the-badge&logo=doom&logoColor=white)
![Platform](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Visual Studio](https://img.shields.io/badge/Visual%20Studio-2022-5C2D91?style=for-the-badge&logo=visual-studio&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-17-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![License](https://img.shields.io/badge/License-GPL--2.0-blue?style=for-the-badge)

**The legendary 1993 FPS, recreated for Windows Console/Terminal**

*Featuring authentic raycasting, full weapon arsenal, classic monsters, and E1M1: Hangar*

[🎮 Download](#-quick-start) • [📖 Features](#-features) • [🎯 Controls](#-controls) • [🔧 Build](#-building-from-source)

</div>

---

## 📸 In-Game Preview

```
====================================================================
==  ####    ####   ####  #   #    DOOM - Console Edition        ==
==  #   #  #    # #    # ## ##                                   ==
==  ####    ####   ####  #   #                                   ==
====================================================================

███████████████░░░░                    ░░░░░░
█████████████████▓▓▓░░              ░░▓▓▓▓▓▓
███████████████████▓▓░            ░░▓▓███████
           I                      ░▓█████████
          III                     ▓▓█████████
         IIIII                    ░▓▓████████
xxxxxxxxxxxxxxxxx                 ░░▓▓▓██████
##################                  ░░▓▓▓███

HP:85 ARM:100 SHOTGUN BUL:45 SHL:12 RKT:0 KILLS:3/10 SCORE:250
```

---

## ✨ Features

### 🎮 Authentic DOOM Experience
- ✅ **Raycasting Engine** - Classic pseudo-3D rendering
- ✅ **E1M1: Hangar** - The legendary first level
- ✅ **Full Menu System** - New Game, Options, Quit
- ✅ **Story Intro** - Knee-Deep in the Dead narrative

### 🔫 Complete Arsenal (8 Weapons)
| # | Weapon | Damage | Ammo | Special |
|---|--------|--------|------|---------|
| 1 | Fist | 10 | ∞ | x10 with Berserk! |
| 2 | Chainsaw | 20 | ∞ | Rapid melee |
| 3 | Pistol | 15 | Bullets | Starting weapon |
| 4 | Shotgun | 70 | Shells | Early powerhouse |
| 5 | Chaingun | 20 | Bullets | Rapid fire |
| 6 | Rocket Launcher | 200 | Rockets | Explosive |
| 7 | Plasma Gun | 40 | Cells | Energy weapon |
| 8 | BFG9000 | 500 | 40 Cells | Ultimate weapon |

### 👾 Classic Monsters
- **Zombieman** (20 HP) - Former humans
- **Imp** (60 HP) - Fireball demons  
- **Demon/Pinky** (150 HP) - Fast melee
- **Cacodemon** (400 HP) - Flying terror
- **Baron of Hell** (1000 HP) - Boss!

### 🎁 All Original Items
**Health**: Bonus, Stimpack, Medikit  
**Armor**: Green (1/3 protection), Blue (1/2 protection)  
**Ammo**: Bullets, Shells, Rockets, Cells  
**Keys**: Blue, Red, Yellow (Keycard & Skull)  
**Powerups**: Berserk, Invulnerability, Invisibility, Rad Suit, Light Amp, Map

---

## 🎮 Controls

```
Movement:          Weapons:           Actions:
W / ↑  Forward     1-8  Select        SPACE  Fire
S / ↓  Backward                       E      Use/Pickup
A / ←  Turn Left                      ESC    Quit
D / →  Turn Right
```

---

## 🚀 Quick Start

### Download & Play
1. Download latest release
2. Extract ZIP
3. Run `DOOM.exe`
4. **RIP AND TEAR!** 🔥

### Building from Source

**Requirements:**
- Windows 10/11
- Visual Studio 2022
- Windows SDK 10.0+

**Build:**
```bash
# Clone repository
git clone https://github.com/YOUR_USERNAME/DOOM-1993-WINDOWS-TERMINAL.git
cd DOOM-1993-WINDOWS-TERMINAL

# Build with Visual Studio
# Open DOOM.sln → Press F7

# OR build with MSBuild
msbuild DOOM.sln /p:Configuration=Release /p:Platform=x64
```

---

## 🎯 Gameplay Guide

### Objective
**Eliminate all 10 enemies and survive!**

### HUD Information
```
HP:100   - Your health (0 = death)
ARM:0    - Armor (absorbs damage)
PISTOL   - Current weapon
BUL:50   - Bullets (Pistol/Chaingun)
SHL:0    - Shells (Shotgun)
RKT:0    - Rockets
CEL:0    - Energy Cells (Plasma/BFG)
KILLS:0/10 - Progress
SCORE:0  - Points
```

### Pro Tips
- 🎯 Conserve ammo - it's limited!
- 🛡️ Collect armor - saves your life
- 💪 Berserk = 100 damage fist!
- 🚀 Use rockets on Baron (1000 HP boss)
- 📍 Watch minimap for enemies (X)
- 🔄 Switch weapons with 1-8 keys

---

## 🏗️ Technical Details

- **Language**: C++17
- **Platform**: Windows Console API
- **Rendering**: Raycasting (like original DOOM)
- **Architecture**: Single-file design
- **Performance**: 30-60 FPS typical

---

## 🎨 Customization

**Add enemies:**
```cpp
monsters.push_back({ x, y, hp, true, 0.0f, type, sprite, maxhp });
```

**Place items:**
```cpp
items.push_back({ x, y, type, subtype, true, sprite });
```

**Modify map:**
```cpp
map += L"####...####";  // # = wall, . = space
```

---

## 🐛 Troubleshooting

| Issue | Solution |
|-------|----------|
| Console looks weird | Run .exe directly, not from VS output |
| Too slow | Build in Release mode |
| Can't compile | Check VS 2022 & Windows SDK installed |
| Can't find enemies | Check minimap (top-left), enemies = X |

---

## 📚 About DOOM

**DOOM** (Dec 10, 1993) revolutionized gaming:
- Pioneered 3D FPS genre
- Introduced multiplayer deathmatch
- Created modding culture
- Released source code (GPL-2.0) in 1997

**Creators:**
- John Carmack - Engine programmer
- John Romero - Level designer
- Tom Hall, Adrian Carmack, Kevin Cloud

---

## 🤝 Contributing

Pull requests welcome! Ideas:
- More levels (E1M2, E1M3...)
- Additional monsters
- Sound effects
- Difficulty settings
- Saved games

---

## 📄 License

**GNU GPL-2.0** (same as original DOOM source)

**DOOM™** is a trademark of id Software / ZeniMax Media.

This is an educational recreation - does not include original assets.  
Buy original DOOM: [Steam](https://store.steampowered.com/app/2280/DOOM/) | [GOG](https://www.gog.com/game/doom_1993)

---

## 🙏 Credits

- **id Software** - Original DOOM creators
- **John Carmack** - Revolutionary engine
- **DOOM Community** - 30+ years of support

---

<div align="center">

**RIP AND TEAR, UNTIL IT IS DONE!** 💀🔫

*1993-2025: 32 years of DOOM* 🎂

⭐ Star this repo if you love DOOM! ⭐

</div>
