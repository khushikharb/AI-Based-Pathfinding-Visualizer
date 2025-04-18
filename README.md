# 🧠 AI-Based Pathfinding Visualizer

An interactive **Pathfinding Visualizer** built using Python and Tkinter that helps users visually understand how different AI algorithms find the shortest path between two points in a grid while avoiding obstacles.

## 🎯 Project Objective

The goal of this project is to help learners, students, and educators visualize and compare the behavior of various pathfinding algorithms. It provides an intuitive, hands-on way to understand search strategies in AI.

---


## ⚙️ Features

- 🟩 Set **Start Node** (Green)
- 🟥 Set **End Node** (Red)
- ⬛ Add/remove **Walls** (Black)
- 🔵 View **Visited Nodes** in real-time
- 🟨 View **Shortest Path** after completion
- ♻️ Reset the grid anytime
- 👨‍💻 Visualize the following algorithms:
  - A* (A-Star)
  - Best-First Search
  - Breadth-First Search (BFS)
  - Depth-First Search (DFS)
  - Hill Climbing

---

## 🧱 Grid Description

The GUI displays a 2D grid (matrix) where:
- Each **cell** represents a node
- Users interactively click to set start, end, and wall nodes
- Algorithms explore the grid from start to end, avoiding wall cells

---

## 🧠 Algorithms

| Algorithm | Description | Optimal? | Complete? |
|----------|-------------|----------|------------|
| **A\*** | Uses `f(n) = g(n) + h(n)` with Manhattan Distance as heuristic | ✅ | ✅ |
| **Best-First Search** | Greedy approach using only `h(n)` | ❌ | ✅ |
| **BFS** | Explores neighbors level-by-level using a queue | ✅ | ✅ |
| **DFS** | Explores deep first using stack | ❌ | ✅ |
| **Hill Climbing** | Greedy heuristic search, stops at local maxima | ❌ | ❌ |

---



