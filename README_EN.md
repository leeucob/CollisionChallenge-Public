# Collision Challenge - Precision Collision Challenge

[![JetBrains Plugins](https://img.shields.io/jetbrains/plugin/v/com.kuyou.CollisionChallenge.svg)](https://plugins.jetbrains.com/plugin/com.kuyou.CollisionChallenge)
[![Commercial Plugin](https://img.shields.io/badge/Status-Commercial-orange.svg)](#commercial-plugin-notice)

[中文版](./README.md) | **English**

**Collision Challenge** is an IDE-embedded physical marble challenge game designed specifically for developers. During coding breaks, take control of the launcher angle to make the marble bounce between obstacles, challenging your spatial reasoning and operational limits.

---

## 🌟 Introduction

Collision Challenge seamlessly integrates into the IntelliJ IDEA interface, providing a highly challenging physical simulation experience through the Tool Window. It is not just a casual game, but a training ground for **precision control** and **logical prediction**.

### Core Highlights:
- **Precision Control**: The heart of the game lies in micro-adjustments of the launcher angle. You must precisely lock the trajectory via the slider or mouse to ensure the marble hits as many obstacles as possible.
- **High Difficulty**: Obstacle layouts are diverse and complex. Every collision changes the marble's kinetic direction; even a slight deviation can lead to falling into the "Elimination Zone" at the bottom, ending the game.
- **Capability Improvement**: By constantly challenging yourself, you can significantly enhance your **spatial logic prediction**, **concentration under pressure**, and **precision in micro-operations**.
- **Scoring Mechanism**: The more obstacles hit, the higher the score. Each collision adds +100 points and grows a snake-like trail, providing visual feedback and a sense of achievement.
- **Data Review**: Use the "Records" function to review the launch angle, collision count, and score of each challenge. Analyze data to find the optimal launch angle and witness your progression from novice to master.

---

## 📷 Screenshots

<p align="center">
  <img src="screenshot/d7692c6e3d3b8a06a5c5fa7af8cf82ff.png" width="18%">
  <img src="screenshot/ef446bbe31a0187a23a3230de39d7b6f.png" width="18%">
  <img src="screenshot/0538e7b0952a6b7f2007cc945fbf4cac.png" width="18%">
  <img src="screenshot/f5996dd9747fac206c39286a9a55dc67.png" width="18%">
  <img src="screenshot/46aef658181b95a850b030c04ab5a81a.png" width="18%">
</p>

---

## ✨ Features

- **Physical Simulation**: Canvas-based real-time physical collision feedback, simulating realistic bounce and kinetic energy.
- **Dynamic Scenes**: Built-in multiple carefully designed level scenes, with obstacles including rectangles, triangles, and other beautified textures.
- **Personalized Themes**: Offers seven beautiful visual themes: Red Brick, Steel Plate, Wood Marble, Stone, Concrete, Leather, and Pebble, catering to different aesthetic preferences.
- **Persistent Records**: All high scores and challenge data are persistently stored in a local JSON file, with support for resetting at any time. The specific directory for the local storage file `CollisionChallengeSettings.json` is: `Windows: C:\Users\[Username]\AppData\Roaming\JetBrains\[IDE version]\config\options\CollisionChallengeSettings.json`

    Note: This path is obtained by `PathManager.getConfigPath()` to get the IDE configuration directory, and then the storage file is created in the `options` folder under it.
- **Multi-language Support**: Native support for Chinese, English, Japanese, and Korean.

---

## 🛠️ Installation

1. Open IntelliJ IDEA.
2. Go to `Settings` (Windows/Linux) or `Settings/Preferences` (macOS).
3. Select `Plugins` and search for **Collision Challenge**.
4. Click `Install` and restart as prompted.
5. After installation, find the **Collision Challenge** icon in the side toolbar to start the challenge.
---
## 🔄 Cross-Version Compatibility

To ensure that the plugin can be launched on the market and verified through various versions of the IDE:
- **Wide Compatibility**: Supports all major versions of IntelliJ IDEA from 2023.1 (Build 231) to 2026.1 (Build 261).
- **Stable Build**: Built on the 2024.1.6 stable SDK to ensure operational stability across different environments.

---
## 💰 Commercial Plugin Notice

**Collision Challenge is a commercial plugin.**

This plugin is commercial software protected by copyright law. We provide a high-quality, continuously maintained simulation experience.

- **Trial Period**: Enjoy a limited free trial period.
- **Official License**: Purchase an official license at the [JetBrains Marketplace](https://plugins.jetbrains.com/plugin/com.kuyou.CollisionChallenge).

---

## 📞 Contact & Feedback

- **Vendor**: LittleRelaxation
- **Contact & Feedback**: If you have any questions or suggestions, please submit an issue on GitHub or visit the plugin page.
- **Marketplace**: [Collision Challenge on Marketplace](https://plugins.jetbrains.com/plugin/com.kuyou.CollisionChallenge)

---

© 2026 LittleRelaxation. All rights reserved.
