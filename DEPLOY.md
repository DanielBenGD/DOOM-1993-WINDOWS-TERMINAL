# 🚀 GitHub Deployment Guide

## Quick Deploy (Recommended)

### Using GitHub CLI (gh)

```bash
# 1. Navigate to project
cd DOOM-1993-WINDOWS-TERMINAL

# 2. Initialize git
git init
git add .
git commit -m "🔥 Initial commit - DOOM 1993 Console Edition"

# 3. Create repo and push (ONE COMMAND!)
gh repo create DOOM-1993-WINDOWS-TERMINAL --public --source=. --push

# Done! 🎉
```

---

## Manual Method

### Step 1: Initialize Git
```bash
cd DOOM-1993-WINDOWS-TERMINAL
git init
git add .
git commit -m "🔥 Initial commit - DOOM 1993 Console Edition"
```

### Step 2: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `DOOM-1993-WINDOWS-TERMINAL`
3. Description: `🔥 DOOM (1993) recreated for Windows Terminal with raycasting, weapons, monsters, and E1M1`
4. Choose: **Public**
5. **DON'T** initialize with README (we already have one)
6. Click **Create repository**

### Step 3: Push to GitHub
```bash
# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/DOOM-1993-WINDOWS-TERMINAL.git

# Push
git branch -M main
git push -u origin main
```

---

## Repository Settings

### After Creating, Set Up:

#### Topics/Tags (for discoverability)
Add these topics:
- `doom`
- `doom-1993`
- `game`
- `fps`
- `raycasting`
- `windows-terminal`
- `console-game`
- `cpp`
- `visual-studio`
- `retro-gaming`

#### About Section
```
🔥 DOOM (1993) recreated for Windows Terminal with authentic raycasting, 
8 weapons, 5 monster types, and E1M1: Hangar. Built with C++17 and Visual Studio 2022.
```

Website: `https://doomwiki.org/`

#### Enable Features
- ✅ Wikis (for documentation)
- ✅ Issues (for bug reports)
- ✅ Discussions (for community)
- ✅ Projects (optional, for roadmap)

---

## Creating a Release

### Step 1: Build Release Version
```bash
# In Visual Studio
# 1. Select "Release" configuration
# 2. Build > Build Solution (F7)
# 3. Find DOOM.exe in x64\Release\
```

### Step 2: Create Release on GitHub
1. Go to your repo
2. Click "Releases" → "Create a new release"
3. Tag: `v1.0.0`
4. Title: `🔥 DOOM Console Edition v1.0.0`
5. Description:
```markdown
## 🎮 First Release!

Classic DOOM (1993) running in your Windows Terminal!

### Features
- ✅ E1M1: Hangar map
- ✅ 8 weapons (Fist to BFG9000)
- ✅ 5 monster types
- ✅ Full item system
- ✅ Raycasting 3D rendering

### Installation
1. Download `DOOM-v1.0.0.zip`
2. Extract
3. Run `DOOM.exe`
4. **RIP AND TEAR!** 🔥

### Requirements
- Windows 10/11
- No additional dependencies!
```
6. Attach: `DOOM.exe` (or create a ZIP with exe + README)
7. Click "Publish release"

---

## Maintenance

### Regular Updates
```bash
# Make changes
git add .
git commit -m "Add: New feature description"
git push
```

### Versioning
Use Semantic Versioning:
- `v1.0.0` - First release
- `v1.1.0` - New features (E1M2 map, new weapon)
- `v1.0.1` - Bug fixes
- `v2.0.0` - Major changes (multiplayer, full episode)

---

## Social Media Sharing

### Twitter/X
```
🔥 Just released DOOM (1993) for Windows Terminal!

✅ Raycasting 3D
✅ 8 weapons
✅ Classic monsters
✅ E1M1: Hangar

Free & open source!
https://github.com/YOUR_USERNAME/DOOM-1993-WINDOWS-TERMINAL

#DOOM #RetroGaming #GameDev #CPlusPlus
```

### Reddit
Good subreddits:
- r/programming
- r/cpp
- r/gamedev
- r/Doom
- r/retrogaming
- r/itrunsdoom

---

## Badges for README

Already included in your README.md! 🎉

```markdown
![DOOM](https://img.shields.io/badge/DOOM-1993-red?style=for-the-badge)
![Platform](https://img.shields.io/badge/Windows-10%2F11-0078D6?style=for-the-badge)
![VS](https://img.shields.io/badge/Visual%20Studio-2022-5C2D91?style=for-the-badge)
![C++](https://img.shields.io/badge/C%2B%2B-17-00599C?style=for-the-badge)
![License](https://img.shields.io/badge/License-GPL--2.0-blue?style=for-the-badge)
```

---

## 🎯 Quick Checklist

Before pushing:
- [ ] All files added
- [ ] .gitignore in place
- [ ] README.md complete
- [ ] LICENSE file present
- [ ] Code compiles without errors
- [ ] Tested on clean machine (if possible)

After pushing:
- [ ] Repository public
- [ ] Topics added
- [ ] About section filled
- [ ] Features enabled (Issues, Wiki)
- [ ] First release created

---

## Need Help?

- GitHub Docs: https://docs.github.com
- Git Basics: https://git-scm.com/book/en/v2
- GitHub CLI: https://cli.github.com/manual/

---

**Now go share your awesome DOOM port with the world!** 🌍🔥

**RIP AND TEAR!** 💀🔫
