# Pixel Art Templates

## Canvas Sizes by Tier

| Tier | Character | Tile | Item | UI Icon |
|------|-----------|------|------|---------|
| 8-bit | 16x16 | 8x8 | 8x8 | 8x8 |
| 16-bit | 32x32 | 16x16 | 16x16 | 16x16 |
| 32-bit | 48x48 | 32x32 | 24x24 | 24x24 |
| 64-bit | 64x64 | 64x64 | 32x32 | 32x32 |
| 128-bit | 128x128 | 128x128 | 64x64 | 48x48 |
| 256-bit | 256x256 | 256x256 | 128x128 | 64x64 |
| 512-bit | 512x512 | 512x512 | 256x256 | 128x128 |
| 1024-bit | 1024x1024 | 1024x1024 | 512x512 | 256x256 |
| 2048-bit | 2048x2048 | 2048x2048 | 1024x1024 | 512x512 |

## Character Animation Frames

### Idle Animation (4 frames)
```
[Frame 1] - Base pose
[Frame 2] - Slight movement (breathing)
[Frame 3] - Base pose
[Frame 4] - Slight movement (alternate)
```

### Walk Cycle (8 frames, 4 directions)
```
Down:  [D1] [D2] [D3] [D4]
Up:    [U1] [U2] [U3] [U4]
Left:  [L1] [L2] [L3] [L4]
Right: [R1] [R2] [R3] [R4]
```

### Run Cycle (6 frames)
```
[Contact] [Down] [Pass] [Contact] [Down] [Pass]
```

## Tile Connections (16-bit and above)

For seamless tiling, create variants:
- **Center** - Full tile
- **Edge N/S/E/W** - Single edges
- **Corner NE/NW/SE/SW** - Outer corners
- **Inner NE/NW/SE/SW** - Inner corners
- **Isolated** - Standalone

## Export Settings

- Format: PNG (transparency)
- Color mode: Indexed (for authentic look) or RGBA
- No anti-aliasing
- Nearest neighbor scaling only
