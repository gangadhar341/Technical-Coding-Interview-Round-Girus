# 🧠 Algorithm Challenges – Python Solutions

This repository contains Python solutions for 5 interesting algorithm problems ranging from matrix traversal to bitwise manipulation and mini language interpretation. Each solution is designed with a beginner-friendly approach.

---

## 📘 Problem 1: Sudoku Validator With Custom Zones

✅ **Goal**: Validate a 9x9 Sudoku board with additional validation of **custom zones**.  
Each custom zone contains 9 arbitrary cells and must also have unique digits from 1 to 9.

### Features:
- Validates rows, columns, and 3x3 boxes
- Validates extra custom-defined zones

---

## 📗 Problem 2: Alien Dictionary

✅ **Goal**: Given a sorted list of words in an alien language, determine the **character order** used in that language.

### Features:
- Builds a graph of character dependencies
- Uses topological sorting (Kahn's algorithm)
- Detects invalid cases (like circular dependencies)

---

## 📙 Problem 3: Knights and Portals

✅ **Goal**: Given a 2D grid of 0s and 1s, find the **shortest path** from top-left to bottom-right.  
You may **teleport once** between any two empty (`0`) cells.

### Features:
- BFS traversal with optional teleport
- Tracks visited cells and teleport usage
- Returns the shortest path distance

---

## 📕 Problem 4: Bitwise Matching Pattern

✅ **Goal**: Given an integer `n`, find the **next greater integer** with the same number of binary `1`s.

### Features:
- Efficient bitwise logic to preserve 1s count
- Handles edge cases (e.g., no larger number possible)
- Works with integers up to 32 bits

---

## 📓 Problem 5: Matrix Islands with Diagonals

✅ **Goal**: Count the number of **islands** (clusters of `1`s) in a matrix.  
Islands can connect in **8 directions** — horizontal, vertical, and diagonal.

### Features:
- DFS-based flood fill algorithm
- Counts disconnected regions of 1s
- Handles any matrix size

---

## 🧮 Bonus: Mini Interpreter

✅ **Goal**: Build a simple interpreter that understands:
- `let` variable declarations
- `if-then-else` expressions
- Basic math and conditionals

### Features:
- Environment to store variable values
- Expression evaluation with arithmetic/comparisons
- Prints output or results based on input lines

---

## 🛠 How to Run

1. Clone the repo or copy the code cells into your **Jupyter Notebook**.
2. Open Jupyter in your browser:
   ```bash
   jupyter notebook

