# Fabric Mob Heights

A lightweight Fabric mod that introduces subtle, realistic height differences while staying true to vanilla gameplay. Inspired by [Variable Mob Height](https://www.curseforge.com/minecraft/mc-mods/vmh), reimagined for Fabric 1.20.1. Fully customizable via Mod Menu.

## 🎯 Features

 - Realistic size variations reflecting natural animal proportions
 - Persistent mob scaling through NBT data   
 - Compatibility with mods & resource packs
 - Customizable scaling ranges via Mod Menu
 - Dynamic adjustments to damage and movement speed
 - Player exclusion for balanced gameplay

## 🔧 Technical Details

- Leverages Pehkui API for smooth scaling implementation
- Maintains door compatibility for humanoid entities
- Includes biome and dimension-specific scaling options
- UUID-based scale caching system
- Periodic cache cleanup to prevent memory leaks
- Configurable through Mod Menu (Game restart required for most options to take affect)
- Simple /resize command for OPs

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
