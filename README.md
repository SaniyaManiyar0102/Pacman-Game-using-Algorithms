# 🟡 Pacman Game Using A* and Dijkstra Algorithms

A Python-based Pac-Man game that uses pathfinding algorithms (A* and Dijkstra's) to simulate intelligent ghost movements. Built with `pygame`, the game offers a classic maze-navigation experience with a focus on algorithmic logic and gameplay mechanics.

---

## 🎮 Game Features

- 🟨 Pac-Man controlled by player
- 👻 Ghosts use **A\*** or **Dijkstra's Algorithm** to chase Pac-Man
- 🍒 Points collected when Pac-Man eats food
- 🧠 Intelligent ghost behavior using real-time pathfinding
- 🎲 Maze implemented as a 2D grid
- 🔄 Easy reset and replay

---

## 🧠 Algorithms Used

### A\* Pathfinding
- Uses a heuristic (Manhattan distance) to efficiently find the shortest path from ghost to Pac-Man.
- Prioritizes nodes based on `f(n) = g(n) + h(n)`, where:
  - `g(n)` is the cost from start to node
  - `h(n)` is the heuristic cost to the goal

### Dijkstra’s Algorithm
- Explores all nodes uniformly without a heuristic.
- Guarantees the shortest path but is slower than A* in larger maps.

---

