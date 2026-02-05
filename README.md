# BlackRoad Pixel Assets

Pixel art assets for the **BlackRoad Metaverse** - original sprites, tiles, and graphics spanning 8-bit to 2048-bit aesthetics.

Inspired by the visual charm of Stardew Valley and Pokemon, but entirely original for BlackRoad.

## Resolution Tiers

| Tier | Canvas Size | Style Reference | Use Case |
|------|-------------|-----------------|----------|
| **8-bit** | 8x8, 16x16 | NES, Game Boy | Icons, tiny sprites |
| **16-bit** | 16x16, 32x32 | SNES, Genesis | Classic RPG sprites |
| **32-bit** | 32x32, 48x48 | PS1, Saturn | Detailed characters |
| **64-bit** | 64x64 | N64, Early PC | HD pixel art |
| **128-bit** | 128x128 | Modern indie | High-detail sprites |
| **256-bit** | 256x256 | HD-2D style | Character portraits |
| **512-bit** | 512x512 | Detailed scenes | Splash art |
| **1024-bit** | 1024x1024 | Ultra HD | Wallpapers, posters |
| **2048-bit** | 2048x2048 | Maximum detail | Hero images |

## Directory Structure

```
assets/
├── 8bit/           # Classic 8-bit sprites (8x8, 16x16)
├── 16bit/          # SNES-era sprites (16x16, 32x32)
├── 32bit/          # Detailed pixel art (32x32, 48x48)
├── 64bit/          # High-res pixel art (64x64)
├── 128bit/         # Modern indie style (128x128)
├── 256bit/         # HD-2D portraits (256x256)
├── 512bit/         # Detailed scenes (512x512)
├── 1024bit/        # Ultra HD pixel art (1024x1024)
└── 2048bit/        # Maximum resolution (2048x2048)

Each tier contains:
├── characters/     # Player, NPCs, enemies, bosses
├── tiles/          # Ground, walls, decorations, terrain
├── items/          # Weapons, tools, consumables, collectibles
├── ui/             # Buttons, frames, icons, cursors
├── effects/        # Particles, magic, explosions, weather
└── backgrounds/    # Parallax layers, skies, environments

palettes/           # Official BlackRoad color palettes
templates/          # Base templates for new assets
animations/         # Sprite sheets and animation frames
tools/              # Scripts for batch processing
```

## BlackRoad Color Palette

Official colors for consistent branding:

| Name | Hex | Usage |
|------|-----|-------|
| Amber | `#F5A623` | Primary accent, gold, energy |
| Hot Pink | `#FF1D6C` | Action, alerts, power |
| Electric Blue | `#2979FF` | Tech, water, interface |
| Violet | `#9C27B0` | Magic, mystery, rare items |
| Pure Black | `#000000` | Backgrounds, shadows |
| Pure White | `#FFFFFF` | Text, highlights |

## Asset Categories

### Characters
- **Player Avatars** - Customizable protagonist sprites
- **NPCs** - Townsfolk, merchants, quest givers
- **Agents** - Octavia (purple), Lucidia (cyan), Alice (green), Aria (blue), Shellfish (red)
- **Enemies** - Creatures, bosses, obstacles
- **Vehicles** - Mounts, ships, machines

### Tiles
- **Terrain** - Grass, dirt, sand, stone, water
- **Buildings** - Houses, shops, stations, ruins
- **Nature** - Trees, flowers, rocks, crystals
- **Tech** - Servers, terminals, circuits, data streams
- **Interiors** - Floors, walls, furniture

### Items
- **Tools** - Pickaxe, hoe, fishing rod, scanner
- **Weapons** - Swords, guns, staffs, drones
- **Consumables** - Food, potions, energy cells
- **Collectibles** - Artifacts, badges, memories
- **Resources** - Ore, wood, data fragments

### UI Elements
- **Buttons** - Actions, navigation, confirmations
- **Frames** - Inventory, dialog, menus
- **Icons** - Status effects, currencies, notifications
- **Cursors** - Selection, targeting, interaction

## Naming Convention

```
[tier]-[category]-[name]-[variant]-[frame].png

Examples:
16bit-characters-player-idle-01.png
32bit-tiles-grass-summer-00.png
64bit-items-sword-fire-equipped.png
128bit-ui-button-primary-hover.png
```

## Animation Format

Sprite sheets use horizontal strips:
- **Idle**: 4 frames
- **Walk**: 8 frames (2 per direction)
- **Run**: 6 frames
- **Attack**: 4-6 frames
- **Special**: Variable

Frame rate: 12 FPS default (83ms per frame)

## Contributing

1. Fork this repository
2. Create assets following the naming convention
3. Use only the official color palette (or extend with permission)
4. Submit PR with preview images
5. Include source files (.aseprite, .psd) when possible

## Tools Recommended

- **Aseprite** - Primary pixel art editor
- **Piskel** - Free browser-based option
- **GraphicsGale** - Animation-focused
- **Photoshop** - With pixel art settings
- **GIMP** - Free alternative

## License

All assets are proprietary to BlackRoad. Internal use only unless explicitly released.

---

**Part of the BlackRoad Metaverse Project**

*Your pixels. Your world. Your rules.*
