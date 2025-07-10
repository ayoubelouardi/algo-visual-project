# Algorithm Visualization Project

> Interactive Data Structure and Algorithm Visualizations

## 📋 Overview

This project is a comprehensive collection of **interactive visualizations** for fundamental data structures and algorithms. Built with HTML5 Canvas and JavaScript, it provides an educational platform for understanding how various algorithms work through step-by-step animations.

Originally created by David Galles at the University of San Francisco, this project serves as an excellent learning resource for computer science students and educators.

## 🎯 Features

### Interactive Visualizations
- **Real-time step-by-step animations** of algorithms
- **User-controlled execution** with play, pause, and step controls
- **Input customization** for testing different scenarios
- **Multi-platform support** (desktop, mobile, tablets)

### Educational Value
- Visual representation of complex algorithmic concepts
- Self-explanatory interface with intuitive controls
- Suitable for classroom demonstrations and self-study
- Covers fundamental to advanced topics in computer science

## 🏗️ Project Structure

```
algo-visual-project/
├── 📁 AlgorithmLibrary/          # Core algorithm implementations
│   ├── Algorithm.js              # Base algorithm class
│   ├── BST.js                    # Binary Search Tree
│   ├── AVL.js                    # AVL Tree
│   ├── Graph.js                  # Graph algorithms
│   └── ... (50+ algorithm files)
├── 📁 AnimationLibrary/          # Animation components
│   ├── AnimatedObject.js         # Base animation objects
│   ├── AnimatedCircle.js         # Animated shapes
│   └── ... (animation utilities)
├── 📁 ThirdParty/               # External dependencies
├── 📁 timages/                  # Image resources
├── 📄 *.html                    # Individual visualization pages
├── 📄 visualPages.css           # Styling for visualization pages
└── 📄 README.md                 # This file
```

## 🧮 Available Algorithms & Data Structures

### 📚 Basic Data Structures
- **Stacks**: Array and Linked List implementations
- **Queues**: Array and Linked List implementations
- **Lists**: Array and Linked List implementations

### 🔄 Recursion
- Factorial calculation
- String reversal
- N-Queens problem

### 🔍 Search & Indexing
- Binary and Linear Search
- **Trees**: BST, AVL, Red-Black, Splay Trees
- **Hash Tables**: Open and Closed addressing
- **Tries**: Prefix trees, Radix trees, Ternary Search Trees
- **B-Trees**: B-Trees and B+ Trees

### 📊 Sorting Algorithms
- **Comparison Sorts**: Bubble, Selection, Insertion, Shell, Merge, Quick Sort
- **Non-comparison Sorts**: Bucket, Counting, Radix, Heap Sort

### 🏔️ Heap Data Structures
- Binary Heaps
- Binomial Queues
- Fibonacci Heaps
- Leftist & Skew Heaps

### 🕸️ Graph Algorithms
- **Traversal**: BFS, DFS, Connected Components
- **Shortest Path**: Dijkstra's, Floyd-Warshall
- **Minimum Spanning Tree**: Prim's, Kruskal's
- **Topological Sort**: Indegree and DFS approaches

### 💡 Dynamic Programming
- Fibonacci sequence calculation
- Making change problem
- Longest Common Subsequence

### 📐 Geometric Algorithms
- 2D/3D Rotation and scaling matrices
- Coordinate system transformations

### 🔧 Other Algorithms
- Disjoint Sets (Union-Find)
- Huffman Coding

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No additional software installation required

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/ayoubelouardi/algo-visual-project.git
   cd algo-visual-project
   ```

2. Open the main page in your browser:
   ```bash
   # Option 1: Open directly
   open Algorithms.html
   
   # Option 2: Start a local server (recommended)
   python -m http.server 8000
   # Then visit: http://localhost:8000/Algorithms.html
   ```

3. Navigate through the available visualizations from the main menu

### Usage Guide
1. **Select an algorithm** from the main algorithms page
2. **Input your data** using the provided controls
3. **Control the animation** with play/pause/step buttons
4. **Observe the visualization** as it demonstrates the algorithm step-by-step

## 🎓 Educational Use

This project is ideal for:
- **Computer Science courses** (Data Structures, Algorithms)
- **Self-study** and exam preparation
- **Teaching demonstrations** in classrooms
- **Interview preparation** for technical roles

## 🤝 Contributing

Contributions are welcome! Please feel free to:
- Report bugs or suggest features
- Submit pull requests for improvements
- Add new algorithm visualizations
- Improve documentation

## 📄 License

This project is based on the original work by David Galles and is distributed under the BSD 2-Clause License. See the license headers in individual files for details.

## 👥 Credits

- **Original Creator**: David Galles, University of San Francisco
- **Current Maintainer**: Ayoub Elouardi
- **Institution**: ALX Software Engineering Program

## 📞 Contact

For questions, suggestions, or collaboration:
- GitHub: [@ayoubelouardi](https://github.com/ayoubelouardi)
- Project Repository: [algo-visual-project](https://github.com/ayoubelouardi/algo-visual-project)

---

*"The best way to understand complex data structures is to see them in action."*
