# Algorithm & Data Structure Visualizer

An interactive educational platform that animates sorting and graph algorithms step-by-step — built to go deeper than lectures and problem sets alone.

> **Status: In Development** — January 2026 – Present

---

## About the Project

This visualizer was built alongside MSU's CSE 331 (Algorithms & Data Structures) to make algorithm behavior genuinely understandable — not just memorizable.

Most resources show you *what* an algorithm does. This shows you *why* one approach outperforms another, with real-time complexity comparisons displayed alongside every animation.

---

## Features

- **10+ algorithms animated** — sorting and graph algorithms with real step-by-step visualization
- **User-controlled speed** — slow down or speed up any animation
- **Step-through mode** — advance one step at a time to understand exactly what's happening
- **Custom input data** — test algorithms on your own arrays and graphs
- **Time & space complexity display** — shown live for each algorithm
- **Visual comparisons** — see why O(n log n) beats O(n²) in practice, not just on paper

---

## Algorithms Implemented

**Sorting**
- Bubble Sort
- Quick Sort
- Merge Sort

**Graph**
- BFS (Breadth-First Search)
- DFS (Depth-First Search)
- Dijkstra's Algorithm

> More algorithms being added continuously.

---

## Tech Stack

| Technology | Purpose |
|---|---|
| React | UI and component state |
| JavaScript | Algorithm logic |
| D3.js | Real-time animations and SVG rendering |

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/sahilsharma370/algo-visualizer.git
cd algo-visualizer

# Install dependencies
npm install

# Start the development server
npm start
```

---

## Project Structure

```
├── src/
│   ├── algorithms/         # Pure algorithm logic (sorting, graph)
│   ├── components/         # Visualizer components per algorithm
│   ├── animations/         # D3.js animation controllers
│   └── utils/              # Complexity data, helpers
└── public/
```

---

## Status

| Feature | Status |
|---|---|
| Bubble, Quick, Merge Sort | 🔨 In Progress |
| BFS, DFS, Dijkstra | 🔨 In Progress |
| Step-through mode | 🔨 In Progress |
| Complexity comparison view | 📋 Planned |
| Custom input support | 📋 Planned |
| Additional algorithms | 📋 Planned |

---

## Why I Built This

I took CSE 331 (Algorithms & Data Structures) at MSU and found that static diagrams in lectures didn't make the *behavior* of algorithms click. This tool is my answer to that — open-sourced so other CSE 331 students and anyone learning algorithms can use it too.

---

## Author

**Sahil Sharma** — [github.com/sahilsharma370](https://github.com/sahilsharma370) · [linkedin.com/in/sahillsharma](https://linkedin.com/in/sahillsharma)
