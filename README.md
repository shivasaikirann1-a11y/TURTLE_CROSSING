# Turtle Crossing Game

## Overview

This project is a simple arcade-style crossing game built using Python’s Turtle graphics module. The player controls a turtle that must cross a busy road while avoiding moving cars. Each successful crossing increases the level and game difficulty.

The project is structured using Object-Oriented Programming principles and split into multiple modules for clarity and maintainability.

---

## Features

* Forward-only player movement using keyboard input
* Randomly generated cars moving across the screen
* Increasing difficulty with each level
* Collision detection system
* Level scoreboard display
* Game over screen on collision

---

## Project Structure

```
turtle_crossing_game/
│
├── main.py          # Runs the game loop and handles coordination
├── player.py        # Player movement and position logic
├── car_manager.py   # Car spawning, movement, and speed control
└── scoreboard.py    # Level tracking and game over display
```

---

## Requirements

* Python 3.x
* Turtle module (comes pre-installed with standard Python)

No external libraries are required.

---

## How to Run

1. Download or clone the project files.
2. Ensure all four files are in the same directory.
3. Run the main file:

```
python main.py
```

---

## Controls

| Key      | Action              |
| -------- | ------------------- |
| Up Arrow | Move turtle forward |

The turtle can only move forward. No backward or sideways movement is allowed.

---

## Game Rules

1. The turtle starts at the bottom of the screen.
2. Cars move horizontally from right to left.
3. If the turtle reaches the top, the level increases.
4. Car speed increases with each level.
5. If the turtle collides with a car, the game ends.

---

## Concepts Demonstrated

* Object-Oriented Programming (OOP)
* Event handling
* Collision detection
* Game loop design
* Animation using Turtle graphics
* Modular code organization

---

## Possible Enhancements

* Add sideways movement
* Introduce lives system
* Add sound effects
* Increase car spawn rate per level
* Save high scores
* Add start / restart menu

---


