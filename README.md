# C++ Data Structures & Algorithms Sandbox

Welcome to the **C++ Data Structures & Algorithms Sandbox**! This repository serves as a practical, hands-on compilation of diverse structural implementations and algorithmic problem-solving in C++. 

Each program features an interactive, CLI-driven environment or benchmarking suite designed to evaluate the operational performance and algorithmic correctness of foundational concepts.

---

## 🛠️ Included Components

### 1. Window Manager ADT
An interactive implementation of a Window Manager subsystem modeled via a custom **Doubly Linked List**. It simulates desktop layout manipulation by executing dynamic node re-ordering.
* **Key Operations:** Create, resize, look up by name, delete, and look up to dynamically shift elements to the head ("Active" window).
* **Core Concepts:** Manual pointer manipulation, structural encapsulation, linear searching.

### 2. Matrix Flood-Fill & Island Detection
A classic grid traversal problem utilizing a recursive **Flood-Fill** strategy to identify isolated components within a 2D matrix.
* **Key Operations:** Dynamically allocates buffered boundary layers, recursively tracks component weights, and aggregates structural components sorted by sizing.
* **Core Concepts:** Multi-dimensional arrays, recursion, Depth First Search (DFS) patterns.

### 3. Binary Search Tree Benchmarking Suite
A completely native implementation of a **Binary Search Tree (BST)** paired with a performance analysis micro-benchmarking tool.
* **Key Operations:** Pointer-based insert, look up, recursive traversal, and complex structural node deletion (handling zero, single, or dual children). Includes an automated table generator displaying operational latency in microseconds.
* **Core Concepts:** Dynamic tree structures, chronological benchmarking (`std::chrono`), memory management/destructors.

---

## 🚀 Getting Started

### Prerequisites
Ensure you have a modern compiler supporting **C++11** or newer (e.g., `g++` or `clang++`).

### Compilation & Execution
You can compile and run any of the files using your terminal. 

**Example for the Window Manager:**
```bash
# Compile the file
g++ -O2 q1.cpp -o window_manager

# Run the executable
./window_manager
