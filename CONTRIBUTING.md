# Contributing to DOOM Console Edition

Thank you for your interest in contributing! 🎮

## How to Contribute

### Reporting Bugs
1. Check if the bug is already reported in [Issues](../../issues)
2. Create a new issue with:
   - Clear title
   - Steps to reproduce
   - Expected vs actual behavior
   - Your system info (Windows version, VS version)

### Suggesting Features
1. Open an issue with the `enhancement` label
2. Describe the feature and why it would be useful
3. Provide examples if possible

### Submitting Code

#### Setup
```bash
# Fork the repository
git clone https://github.com/YOUR_USERNAME/DOOM-1993-WINDOWS-TERMINAL.git
cd DOOM-1993-WINDOWS-TERMINAL

# Create a branch
git checkout -b feature/your-feature-name
```

#### Making Changes
1. Write clean, commented code
2. Test your changes thoroughly
3. Ensure it compiles without warnings
4. Follow the existing code style

#### Submitting
```bash
# Commit your changes
git add .
git commit -m "Add: Your feature description"

# Push to your fork
git push origin feature/your-feature-name

# Open a Pull Request
```

## Code Style

- **Indentation**: 4 spaces (no tabs)
- **Naming**: 
  - Variables: `camelCase` or `snake_case`
  - Constants: `UPPER_CASE`
  - Functions: `PascalCase` or `camelCase`
- **Comments**: Explain WHY, not WHAT
- **Max line length**: 100 characters

## Feature Ideas

Here are some ideas if you want to contribute:

### Easy
- [ ] Add more health/ammo pickups
- [ ] Increase enemy variety in E1M1
- [ ] Add color variations for monsters
- [ ] Implement key-locked doors

### Medium
- [ ] Create E1M2 (Nuclear Plant) map
- [ ] Add more powerups (Megasphere, Soul Sphere)
- [ ] Implement secret areas
- [ ] Add sound effects using Windows Beep API
- [ ] Create difficulty levels (I'm Too Young To Die → Nightmare)

### Hard
- [ ] Full Episode 1 (9 levels)
- [ ] Save/Load game system
- [ ] Demo recording/playback
- [ ] Network multiplayer (co-op or deathmatch)
- [ ] WAD file loader
- [ ] Texture mapping on walls

## Testing

Before submitting:
1. Build in both Debug and Release
2. Test on a clean Windows install if possible
3. Verify all features work
4. Check for memory leaks (if applicable)

## Questions?

Feel free to ask in:
- [Discussions](../../discussions)
- [Discord](#) (if applicable)

## Code of Conduct

- Be respectful and constructive
- Welcome newcomers
- Focus on the code, not the person
- Have fun! This is DOOM! 🔥

---

**Thank you for contributing to keeping DOOM alive!**

RIP AND TEAR! 💀🔫
