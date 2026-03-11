# 2048-Enhanced

An enhanced implementation of the classic 2048 game built using Java and the Processing graphics library.
This version contains additional mechanics and a structured Gradle project setup.

---

## Features

* Classic 2048 tile merging gameplay
* Smooth tile movement animations
* Random tile spawning (2 or 4)
* Tile spawning by mouse click
* Game over detection
* Game timer
* Restart functionality
* Configurable grid size
* Built using Processing library for graphics
* Managed with Gradle

---

## Gameplay

The game is played on a grid of size 4 (Can be changed).

Players move tiles using the arrow keys.
When two tiles with the same value collide, they merge into a tile with double the value.

After every move, a new tile (2 or 4) appears randomly on the board. You can also click on a cell to generate a random tile (2 or 4)


---

## Controls

| Key | Action           |
| --- | ---------------- |
| ⬆️  | Move tiles up    |
| ⬇️  | Move tiles down  |
| ⬅️  | Move tiles left  |
| ➡️  | Move tiles right |
| R   | Restart the game |

---

## Technologies Used

* Java
* Processing Graphics Library
* Gradle

---

## How to Run

```
gradle run
```

This will compile the project and launch the game window.

---

## License

This project is licensed under the **MIT License**.
