# Mirai

All-in-one mining AI for Mindustry (v8, build 160.7). It comes as three logic schematics: **Mirai Advanced**, **Mirai Standard** and **Mirai Lite**. Paste one next to your base and it runs mining, defense and dome upkeep for your units by itself.

## Versions

| Version | Size | Workers | Blocks |
|---|---|---|---|
| Advanced | 12x11 | 16 | 55 |
| Standard | 10x9 | 8 | 43 |
| Lite | 8x9 | 4 | 40 |

Each one is a full rectangle with no empty tiles. It includes a 3x3 overdrive dome, a memory bank, a brain processor, 7 switches and status messages.

## Features

- **Automatic mining.** Tracks the stock and rate of every ore, sends units to the most needed ones and spreads them over the veins.
- **Scales to 1000+ units.** Each unit's state lives in its flag, so there is no slot limit. Tested with 1200 live units.
- **Core guard.** Armed units defend the core when it takes damage or an enemy gets close.
- **Healing and fleeing.** Hurt units go to repair points. Miners run from enemies and mark the vein unsafe.
- **Hunting.** Nearby armed units attack weak enemies far from the core.
- **Idle ring.** Units with nothing to mine wait spread around the core.
- **Erekir aware.** Only compatible items go to Erekir cores. The rest go to a Serpulo core.
- **No-mining zones.** Up to 8 zones where units won't mine.
- **Server-safe.** Every processor config is under 1100 B, there are no privileged instructions and units held by players or other processors are never taken.

## How to use

1. Download a `.msch` from the [latest release](../../releases/latest) and import it from the Schematics menu.
2. Place it anywhere. No links or core link are needed.
3. Power the dome (10/s) and keep phase and silicon in the core.
4. Optional: build repair points near the core.

Settings (ore priorities, units per vein, which unit types to use, guard radius and more) are at the top of the brain processor. Each switch has a message next to it that says what it does.

## License

MIT, see [LICENSE](LICENSE).

## Author

Duskaraa
