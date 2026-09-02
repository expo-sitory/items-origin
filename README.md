# Items Origin

Track which player originally obtained tools and armor on Paper 1.21.x

## What it does

When a player picks up or equips a tool or piece of armor for the first time, this plugin automatically adds a lore line showing who originally obtained it. Useful for identifying item sources in survival economies or preventing untraceable gear in competitive modes.

**Example:**
```
Iron Pickaxe
Origin: Steve
```

## Tracked Items

- **Tools**: Pickaxe, Axe, Shovel, Hoe, Sword (Iron, Gold, Diamond, Netherite)
- **Armor**: Helmet, Chestplate, Leggings, Boots (Iron, Gold, Diamond, Netherite)
- **Weapons**: Mace, Trident, Bow, Crossbow, Shield
- **Spears** (if available in your version)

## Installation

1. Download the JAR from releases
2. Drop into your plugins folder
3. Restart server

No configuration needed—it works out of the box.

## How it works

- When a player holds a tracked item that hasn't been marked yet, the origin lore is automatically added
- Only marks items once; won't overwrite existing origin markers
- Uses red text for the origin line for visibility

## Requirements

- Paper 1.21+
- Java 21+

## Build

```bash
mvn clean package
```
