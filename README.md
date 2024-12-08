# Fabric Mob Heights

A lightweight Fabric mod that introduces subtle, realistic height differences while staying true to vanilla gameplay. Inspired by [Variable Mob Height](https://www.curseforge.com/minecraft/mc-mods/vmh), reimagined for Fabric 1.20.1. Fully customizable via Mod Menu.

## 🎯 Features

 - Realistic size variations reflecting natural animal proportions
 - Persistent mob scaling through NBT data   
 - Compatibility with mods & resource packs
 - Customizable scaling ranges via Mod Menu
 - Dynamic adjustments to damage and movement speed
 - Player exclusion for balanced gameplay
 - Biome Integration: Mob sizes adapt to their environment

## 🔧 Technical Details

- Leverages Pehkui API for smooth scaling implementation
- Maintains door compatibility for humanoid entities
- Includes biome and dimension-specific scaling options
- UUID-based scale caching system
- Periodic cache cleanup to prevent memory leaks
- Configurable through Mod Menu (Game restart required for most options to take affect)
- Simple /resize <size> and /resize undo commands for OPs

## 🌍 Biome Scaling System

The mod dynamically adjusts mob sizes based on their spawn biome. Each biome has unique scaling factors that affect mob sizes in logical ways. Modded biomes use a default 1.0x multiplier, while biomes that share categories with vanilla biomes automatically inherit their vanilla counterparts' scaling factors.

<details>
<summary>Spoiler</summary>

| Biome Type | Size Multiplier | Reasoning |
|------------|-----------------|-----------|
| Jungle | 1.3x (30% larger) | Abundant resources and space |
| Desert | 1.2x (20% larger) | Adaptation to open terrain |
| Plains | 1.0x (baseline) | Standard reference size |
| Swamp | 0.8x (20% smaller) | Dense vegetation adaptation |
| Mountains | 1.15x (15% larger) | Higher altitude adaptation |
| Forest | 0.9x (10% smaller) | Forest canopy adaptation |
| Savanna | 1.1x (10% larger) | Open grassland adaptation |
| Tundra | 1.2x (20% larger) | Cold climate adaptation |
| Beach | 0.85x (15% smaller) | Coastal environment adaptation |
| Ocean | 1.25x (25% larger) | Aquatic environment adaptation |

</details>



## 📦 Requirements

- Minecraft 1.20.1
- Fabric API
- Pehkui
- Cloth Config API
- Mod Menu

## 🏗️ Planned Features
- Size inheritance for bred animals
- Time-based size variations (mobs spawn larger at night)

## 🐛 Bug Reports

Found an issue? Please report it on the [GitHub Issue Tracker](https://github.com/ghostmalls/Fabric-Mob-Height/issues).
