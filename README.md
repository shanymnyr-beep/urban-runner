# Urban Runner

A 3D behind-view endless lane runner built with pure HTML5 Canvas + JavaScript. No frameworks, no external assets, all art drawn in code.

## Play

Open `index.html` in any browser, or enable **GitHub Pages** (Settings → Pages → deploy from `main`) and play at:
`https://shanymnyr-beep.github.io/urban-runner/`

## Controls

- **Left / Right** (arrows, A/D, or swipe): switch lanes
- **Up** (arrow, W, Space, tap, or swipe up): jump
- **Down** (arrow, S, or swipe down): slide
- **Esc**: pause

## Features

- 3-lane pseudo-3D perspective runner with rising difficulty
- Obstacles: crates, cones, barrels, fire, spikes, and overhead barriers (slide under)
- Collectibles: coins, gems, and 5 power-ups (magnet, shield, rocket, speed boost, 2X score)
- Character shop with 7 unlockable runners (coins & gems)
- Skills upgrade system, settings, and full progress saving (localStorage)

## Files

- `index.html` — markup, styling, and all screens
- `game.js` — game engine, rendering, and logic
