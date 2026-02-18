# Shared Assets

Shared asset repository for use across multiple projects via git submodules.

## Structure

```
sprites/          Character sprites, objects, visual effects
  characters/     Player, enemies, NPCs (49 packs)
  objects/        Items, props, collectibles, planets (16 packs)
  effects/        Particles, explosions, glows (3 packs)
icons/            Icons for apps and games
  game/           In-game icons (coins, gems, power-ups)
sounds/           Audio assets
  sfx/            Sound effects
  music/          Background music, loops
fonts/            Pixel and game-friendly fonts (11 families)
ui/               UI components
  buttons/        Button sprites
  panels/         Panels, frames, windows
  dialogs/        Dialog boxes, popups
  hud/            HUD elements (health bars, counters)
backgrounds/      Background images, parallax layers
tilesets/         Tile-based map assets and textures (15 packs)
animations/       Sprite sheets, animation sequences
models/           3D models (FBX, OBJ)
kenney/           Kenney Game Assets All-in-1 (massive collection)
```

## Asset Packs Included

### 2D Game Assets
- Pixel Adventure 1, Pixel Crawler, Pixel Dungeon, Pixel Art Top Down
- Ninja Adventure, Mystic Woods, Cute Fantasy, Tiny Swords
- Sunnyside World v2.1, Sprout Lands, Farm RPG 16x16
- Modern Interiors, Mossy Tileset, Brackeys Platformer
- Mana Seed Character Base, Blue Wizard, Enemy Animations
- 30+ character/creature animation packs
- Legacy Collection, Chess pieces

### 3D Models
- KayKit Adventurers 2.0, KayKit Forest Nature
- Stylized Nature MegaKit

### Kenney Collection
- 140+ 2D asset packs (platformer, RPG, shooter, puzzle, etc.)
- 3D assets, Audio, UI assets, Icons

### Fonts
- Pixel: Press Start 2P, Silkscreen, VT323, Coral Pixels, Pixelify Sans
- Display: Rubik Pixels, Dot Gothic 16, Turret Road, Pixel Operator
- Body: Roboto Slab

### SBS Texture & Planet Packs
- 2D Planet Pack (128/256/512) - 17 planet types
- 2D Planet Pack 2 (Shaded + Unshaded, 128/256/512)
- Planet Textures Addon
- Abstract Texture Pack (128/256/512)
- Base Materials Pack (128/256/512)
- Photorealistic Texture Pack 1/2/3 (128/256/512)
- Sandbox Style Terrain (bricks, textures, cubes)
- Seamless Abstract Pack (128/256/512)
- Tiny Texture Pack 1/2/3 (multiple sizes)
- Isometric Crate Textures & Packs (64/128)
- Portrait Frame Pack (128/256) - Marble, Metal, Plastic, Stone, Wood

### UI
- Free Buttons, Pixel UI Pack 3
- SBS Portrait Frames
- Per-pack UI elements in hud/panels subdirectories

## Usage

Add as a submodule in another project:
```bash
git submodule add https://github.com/LightWraith8268/shared-assets.git assets
```
