# Cow in the Ship 🐄🚀

A simple pygame-based game where you control a UFO to collect cows!

## Description

In this game, you control a UFO using arrow keys. Your goal is to catch the cow by moving the UFO over it. When you successfully catch a cow, it will teleport to a random location on the screen, and you'll see a "Cow in the Ship!" message.

## Requirements

- Python 3.x
- pygame library

## Installation

1. Make sure you have Python installed on your system.

2. Install pygame using pip:
```bash
pip install pygame
```

## How to Run

1. Make sure you have the following files in the same directory:
   - `cow in the ship.ipynb` (Jupyter notebook)
   - `ufo.png` (UFO image)
   - `cow (1).png` (Cow image)

2. Open the Jupyter notebook:
```bash
jupyter notebook "cow in the ship.ipynb"
```

3. Run all cells in the notebook.

Alternatively, you can convert the notebook to a Python script and run it directly.

## Controls

- **Arrow Keys**: Move the UFO
  - `←` Left Arrow: Move left
  - `→` Right Arrow: Move right
  - `↑` Up Arrow: Move up
  - `↓` Down Arrow: Move down

## Game Features

- Smooth UFO movement with arrow key controls
- Collision detection between UFO and cow
- Random cow respawning after collection
- 165 FPS gameplay for smooth experience
- Visual collision rectangles (red borders) for debugging

## Game Settings

- Window size: 700x800 pixels
- Movement speed: 5 pixels per frame
- FPS: 165

## Files

- `cow in the ship.ipynb` - Main game code (Jupyter notebook)
- `ufo.png` - UFO sprite image
- `cow (1).png` - Cow sprite image

## Notes

- The red rectangles around the UFO and cow are collision boundaries used for debugging.
- The cow will respawn at a random location each time it's collected.
- Close the game window to exit the game.

Enjoy playing! 🎮
