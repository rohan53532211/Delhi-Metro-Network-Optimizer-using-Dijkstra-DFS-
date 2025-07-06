# 🚇 Delhi-Metro-Network-Optimizer-using-Dijkstra-DFS-

A C++ project that simulates a metro navigation system by computing the shortest distance, time, and path between stations using classic graph algorithms like Dijkstra, BFS, and DFS.

---

## 🎯 Objective

To develop a command-line tool that helps users find the shortest metro route based on source and destination inputs, using efficient graph-based algorithms.

---

## 🧠 Features & Approach

- Used **Graph** and **Heap** data structures to represent stations and edge weights (distances).
- Implemented **Dijkstra’s Algorithm** to compute shortest distances and travel time.
- Used **BFS** and **DFS** for station traversal and route display.
- Provided a **menu-driven interface** to display:
  - All stations
  - Metro map structure
  - Shortest distance and time
  - Exact travel path between stations

---

## 🛠️ Technologies Used

- C++
- STL (Vectors, Maps, Priority Queues)
- Graph Algorithms (Dijkstra, BFS, DFS)

---

## 📂 Project Structure

- `main.cpp` – Main logic and menu interface
- `graph/` – Graph structure and edge definitions
- `algorithms/` – Pathfinding logic (Dijkstra, BFS)
- `README.md` – Project documentation

---

## 💡 Sample Actions (via console)

1. List all stations  
2. Show metro map (graph traversal)  
3. Get shortest distance or time  
4. Display path from source to destination  

---

## 📌 Future Improvements

- GUI integration with Qt or Tkinter  
- Real-time station info or delays  
- Fare estimation based on distance

---

## 📄 License

This project is open-sourced under the MIT License.
