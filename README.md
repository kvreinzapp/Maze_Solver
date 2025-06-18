# Terminal Maze Pathfinding Visualizer

A simple and fun terminal-based visualizer using Python's `curses` module to demonstrate **breadth-first search (BFS)** pathfinding through a maze.

---

## 🎯 Features

- 🧱 Maze rendered in terminal with walls (`#`), start (`O`), and end (`X`)
- 🔎 Uses BFS to find the shortest path
- 🎨 Visualizes search progress using live animation
- 🧠 Educational tool for learning pathfinding and `curses`

---

## 🛠️ How to Run

### 1. Requirements

- Python 3.6+
- macOS/Linux (or Windows with Windows Terminal or WSL)

### 2. Run the script

```bash
python maze_solver.py
````

---

## 🎨 Controls & Symbols

* `O` — Start point
* `X` — End/goal
* `#` — Wall
* `X` (red on screen) — Current path being explored

---

## 🧠 How It Works

* Finds the starting position `"O"` in the maze
* Uses a **queue** to explore all possible paths (BFS)
* Updates the terminal on each step using `curses`
* Stops when the end `"X"` is reached and shows the found path

---

## 🗺️ Maze Example

```text
# O # # # # # # #
#               #
#   # #   # #   #
#   #     #     #
#   #   # #     #
#   #   # #     #
#   #   # ##### #
#               #
# # # # # # # X #
```

---

## 🧩 File Overview

```
maze_solver.py   # Main script with curses-based visualizer and BFS logic
```

