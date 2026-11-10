# Pac-Man

A browser-playable Pac-Man arcade prototype, built as a single HTML canvas game with a pixel sprite sheet.

## Play

Open [index.html](index.html) in a modern browser, or serve this folder locally:

```sh
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

Use the arrow keys or WASD to steer. Press Space to pause. On touch screens, use the on-screen directional pad.

## Files

- `index.html` — game, rendering, movement, collisions, and animations
- `pacman-sprites.png` — source sprite atlas used by the game

The game has no build step or external runtime dependencies.
