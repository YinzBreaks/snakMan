# SnakMan (The Resistance Arcade Cabinet 3)

A standalone, production-ready single-file HTML5 Canvas arcade game with zero external dependencies.

## Features
- **Procedural Bunker Maze**: 28×36 logical coordinate grid with high-DPI canvas scaling, double-bordered gilded gold moldings (`#fbbf24`), cracked slate bunker flooring (`#1e293b`), and side warp tunnels on Row 17.
- **Collectibles**:
  - Procedural Mini-Burgers (golden bun, patty, ketchup) worth 10 points.
  - 4 Corner Power Diet Drinks with red-and-white striped straws worth 50 points (activating **Executive Immunity**).
- **Pac-Don Controller**:
  - Grid-aligned movement with pre-turn directional buffering.
  - Signature procedural sprite: intense orange circular body, oscillating chomping wedge mouth, golden pompadour hair crest, and pale raccoon eye circles with squinting eye slots.
  - Base 80% tile speed; accelerates by +15% during Executive Immunity.
- **Sub-Basement Evidence Locker**:
  - Center ghost pen labeled "Sub-Basement Evidence Locker" with animated gilded security gate bars.
  - 4 Federal Agent ghosts with custom pursuit and scatter behaviors.
  - Terrified Frightened state during Executive Immunity with score popups (+200, +400, +800, +1600).
- **Web Audio API Synth Engine**:
  - Procedural 55Hz subterranean bunker hum with lowpass filter and LFO breathing modulation.
  - Rapid wet-biting chomp synth (~140Hz square wave with steep pitch drop) alternating pitch on every burger eaten.
  - Sweeping slurp tone (400Hz to 1200Hz) with resonant bandpass filter and straw bubble flutter.
  - Sound effects for eating agents, losing lives, and game over.
- **Controls**:
  - Keyboard: Arrow keys, WASD, Space (start / restart).
  - Mobile / Touch: Canvas swipe detection and responsive on-screen virtual D-pad.

## Quick Start
Open `index.html` in any modern web browser. Zero build steps or dependencies required.
