# V29 Fixed — Customize Guide

## Story text
Open `index.html` and search for `CUSTOMIZE HERE`.

## Backgrounds
Replace files while keeping filenames:
- `assets/backgrounds/opening.png`
- `assets/backgrounds/world-map.png`
- `assets/backgrounds/taiwan.png`
- `assets/backgrounds/germany.png`
- `assets/backgrounds/korea.png`
- `assets/backgrounds/final.png`

## Player sprites
Replace files in `assets/players/`.

## Collectibles
Replace files in each country folder under `assets/collectibles/`.

## Music
Replace `assets/music/bgm.mp3`, then change the `CUSTOMIZE_HERE.audio.src` value to `assets/music/bgm.mp3`.

## Keep the engine stable
Do not edit `makeLevel`, `updateGame`, route/progress logic, gravity/jump, or collision code unless you intentionally want to change gameplay.
