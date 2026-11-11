# Pac-Man

A browser-playable Pac-Man arcade prototype.

## Run locally

Serve this folder with a local web server:

```sh
python3 -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000).

Use the arrow keys or WASD to steer. Press Space to pause. Touch screens have an on-screen directional pad.

## Sprite sheets

- `pacman-sprites.png` supplies the maze and character animation art.
- `pacman-sprites-new.png` supplies the PAC-MAN title, READY and GAME OVER labels, score digits, and bonus fruit. The attribution text in the sheet's upper-right corner is not used.

The game has no build step or external runtime dependencies.
