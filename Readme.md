# 🚀 Cosmic Defender

![Cosmic Defender Logo](Resources/Logo.svg)

## Terminal-based Space Adventure on Windows

**Cosmic Defender** is an exciting terminal-based space shooter game written in Swift and designed to run on Windows systems. Defend the galaxy from relentless alien invaders using only your ship and your wits!

## 📖 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Play](#how-to-play)
- [Controls](#controls)
- [Game Mechanics](#game-mechanics)

## Overview

In a distant future, humanity's last outpost is under attack from alien forces seeking to destroy everything in their path. As the pilot of the experimental spacecraft "Defender," you are tasked with protecting your home against waves of enemy ships, collecting power-ups, and upgrading your vessel to face increasingly difficult challenges.

Cosmic Defender brings classic arcade shooting action to your terminal window with colorful ASCII graphics, immersive sound effects (via console beeps), and challenging gameplay - all without leaving your command line.

## Features

- 🌌 Vibrant ASCII/Unicode art in your terminal
- 🎮 Smooth, responsive controls
- 👾 Multiple enemy types with unique attack patterns
- 🔧 Ship upgrades and power-ups
- 🎵 Dynamic sound effects using terminal beeps
- 📊 High score tracking
- 🔄 Progressive difficulty system
- 💾 Save game functionality

## Requirements

- Windows 10 or later
- Swift for Windows (version 6.0 or later)
- Terminal with Unicode support and ANSI color capability (Windows Terminal recommended)
- Minimum terminal size: 120x40 characters

## Installation

1. **Install Swift for Windows using Winget**:
   - Enable Developer Mode (Settings > Update & Security > For developers > Developer mode)
   - Install Windows platform dependencies:

      ```powershell
      winget install --id Microsoft.VisualStudio.2022.Community --exact --force --custom "--add Microsoft.VisualStudio.Component.Windows11SDK.22000 --add Microsoft.VisualStudio.Component.VC.Tools.x86.x64 --add Microsoft.VisualStudio.Component.VC.Tools.ARM64"
      ```

   - Install Swift and other dependencies:

      ```powershell
      winget install --id Swift.Toolchain -e
      ```

2. **Download Cosmic Defender**:

   ```bash
   git clone https://github.com//cosmic-defender.git
   cd cosmic-defender
   ```

3. **Build the game**:

   ```bash
   swift build -c release
   ```

4. **Run the game**:

   ```bash
   swift run -c release
   ```

## How to Play

Launch the game and navigate the main menu using the keyboard. Select "New Game" to begin your adventure or "Tutorial" to learn the basics of ship control and combat.

Your objective is to survive increasingly difficult waves of enemies while scoring as many points as possible. Collect power-ups to enhance your ship's capabilities and defeat boss enemies to progress to new sectors of space.

## Controls

| Key           | Action                    |
|---------------|---------------------------|
| W / ↑         | Move Up                   |
| S / ↓         | Move Down                 |
| A / ←         | Move Left                 |
| D / →         | Move Right                |
| Spacebar      | Fire Primary Weapon       |
| E             | Activate Shield           |
| Q             | Deploy Special Weapon     |
| Tab           | Cycle Weapons             |
| P             | Pause Game                |
| ESC           | Menu / Quit               |
| 1-4           | Quick Select Weapons      |

## Game Mechanics

### Ship Systems

- **Hull Integrity**: Your ship's health. Repairs slowly over time.
- **Shield Energy**: Absorbs damage but depletes quickly and recharges slowly.
- **Weapon Energy**: Used for firing weapons, recharges moderately.
- **Special Energy**: Powers your special abilities, recharges slowly.

### Power-ups

- 🔷 **Blue Orb**: Restores shield energy
- ❤️ **Red Heart**: Repairs hull damage
- ⚡ **Lightning**: Weapon energy boost
- 🌟 **Star**: Special energy boost
- 🔥 **Flame**: Temporary weapon upgrade
- 💠 **Diamond**: Score multiplier
- 🔄 **Cycle**: New special ability

### Enemies

- **Drones**: Fast but fragile
- **Fighters**: Balanced attack and defense
- **Cruisers**: Slow but heavily armored
- **Carriers**: Spawn smaller ships
- **Bosses**: Unique attack patterns and vulnerabilities

---

"The cosmos awaits your defense, Commander. Good luck!"
