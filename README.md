# 🧩 A* Maze Solver (C++ / Qt)

A high-performance, visual maze solving application built in **C++** using the **Qt Framework**. This project demonstrates the practical implementation of the **A* (A-Star) search algorithm** to find the shortest path between two points in a grid-based environment.



## 🚀 About The Project

This project was developed as my first task during my **Artificial Intelligence Internship at Syntecx Hub**. The goal was to build a robust pathfinding visualizer that demonstrates how heuristic search algorithms work in real-time.

The application features a fully interactive Graphical User Interface (GUI) where users can visualize the agent finding the optimal path through a maze.

## 🛠️ Tech Stack

* **Language:** C++ (Standard 11/14/17)
* **Framework:** Qt (Widgets/Quick)
* **IDE:** Qt Creator
* **Algorithm:** A* Search (Heuristic-based Pathfinding)

## ✨ Key Features

* **Visual Pathfinding:** Watch the A* algorithm explore nodes and calculate costs in real-time.
* **Interactive UI:** Clean interface built with Qt to generate mazes and trigger solvers.
* **Optimized Performance:** Efficient memory management and fast execution using C++.
* **Heuristic Calculation:** Implements Manhattan/Euclidean distance for optimal path scoring.

## 📷 Screenshots

*(Place a screenshot of your application here. It is highly recommended to show the UI with a solved path.)*

## 🔧 Installation & Setup

1.  **Prerequisites:** Ensure you have **Qt Creator** and a compatible C++ compiler (MinGW/MSVC/GCC) installed.
2.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/your-username/maze-solver-qt.git](https://github.com/your-username/maze-solver-qt.git)
    ```
3.  **Open Project:**
    * Launch Qt Creator.
    * Open the `CMakeLists.txt` or `.pro` file.
4.  **Build & Run:**
    * Configure the project kit.
    * Click the **Run** button (or press `Ctrl+R`).

## 🧠 Algorithm Overview

The **A* Algorithm** is used here because it combines the benefits of Dijkstra’s Algorithm (guaranteeing the shortest path) and Greedy Best-First-Search (efficiency).

* **F-Cost:** G-Cost (distance from start) + H-Cost (distance to end).
* **Heuristic:** Estimates the cost to reach the goal, prioritizing promising paths.

## 🤝 Acknowledgments

* **Syntecx Hub** for providing the internship opportunity and mentorship.
* Qt Documentation for GUI references.
