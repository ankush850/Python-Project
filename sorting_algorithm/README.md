# Iterative Shift-and-Compare Sorting Algorithm

## 📌 Project Overview
A foundational algorithm exploration script implementing a custom iterative comparison, shifting, and reconstruction sorting mechanism in Python.

The algorithm generates an unordered list of randomized integers, iteratively reorders adjacent elements into a new buffer, verifies the ascending sorted order property across each pass, and outputs execution benchmarks.

---

## 🔬 How it Works
1. Populates a test list of random integers.
2. Iterates over neighboring elements, comparing values and relocating the smaller/larger values into a secondary accumulator list.
3. Performs a validation pass checking if $A[i] \le A[i+1]$ across all elements.
4. Terminates and returns the sorted sequence once full ascending order is achieved.

---

## 📦 Requirements & Installation
This project runs entirely on the **Python Standard Library** (`random`, `time`) and does not require third-party libraries.

---

## 🚀 How to Run
Execute the script from the terminal:

```bash
python sorting_algorithm.py
```
