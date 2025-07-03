# 🧭 PathCrafter

**PathCrafter** is a C++ based pathfinding visualizer that brings classic graph algorithms like **A\*** and **Dijkstra’s Algorithm** to life through real-time animations. It's a powerful tool to understand how pathfinding works across grids, walls, and weighted nodes.

---

## 🚀 Features

- 🧠 **A\*** and **Dijkstra’s Algorithm** implementations  
- 🟩 Interactive grid creation: start, end, and walls  
- 🖱️ Mouse-based placement and controls  
- 🎞️ Real-time step-by-step visualization  
- ⚙️ Simple and fast SFML-based GUI  
- 🧱 Customizable grid size, speed, and colors

---


## 🛠️ Tech Stack

- **Language:** C++  
- **Graphics Library:** [SFML](https://www.sfml-dev.org/)  
- **Build System:** g++ / Visual Studio  

---

## 📦 Setup Instructions

### ✅ Prerequisites

- C++17 compiler (g++, clang, or MSVC)
- SFML library installed

### 🧑‍💻 Build & Run

#### Using CMake

git clone https://github.com/ultimateebeast/PathCrafter.git
cd PathCrafter
mkdir build && cd build
cmake ..
make
./PathCrafter
Or Directly (Linux/macOS)

g++ -std=c++17 main.cpp -o PathCrafter -lsfml-graphics -lsfml-window -lsfml-system
./PathCrafter
On Windows (Visual Studio)
Open PathCrafter.sln in Visual Studio

Build & Run

🎮 How to Use
Left Click to place:

Green: Start Node

Red: End Node

Black: Walls

Right Click to erase a node

Press Space to start visualization

Press C to clear the board

📁 Project Structure

PathCrafter/
│
├── src/                 → Main source files
├── include/             → Header files
├── assets/              → Icons, images (if any)
└── README.md            → You're here!
📚 Algorithms Explained
🔷 Dijkstra’s Algorithm: Guarantees shortest path using a priority queue.

⭐ A*: Heuristic-based search for faster and smarter pathfinding.

Both operate on a grid and highlight visited paths step-by-step.

🧠 Inspiration
Built to help students and developers understand graph algorithms visually, especially useful for interview prep and DSA revision.

📝 License
This project is licensed under the MIT License.

🤝 Contributing
Pull requests are welcome! Feel free to:

Add new algorithms (BFS, DFS, etc.)

Improve grid rendering

Add more controls or a better UI

👤 Author
Made with ❤️ by Pratyush Jain
📬 Reach me via GitHub or raise an issue.
