# Fibonacci Heap vs Binary Heap in Dijkstra

Final Project – HCMUTE 02/2025

Final coursework for the course
Data Structures and Algorithms (ALDS335764)

---

## Project Summary

This project compares the use of Fibonacci Heap and Binary Heap in Dijkstra's algorithm. The analysis is based on amortized cost using the potential method.

### Features

* Full Fibonacci Heap implementation: insert, extract_min, decrease_key
* Dijkstra's algorithm implemented with both heaps
* Benchmark with custom node range from 2 up to more than 10000
* MATLAB script for automatic plotting
* PNG chart export for performance comparison

---

## File Overview

| File                   | Description                                   |
| ---------------------- | --------------------------------------------- |
| main.py                | Core implementation (heap, Dijkstra, testing) |
| dijkstra_benchmark.m   | MATLAB script for plotting benchmark results  |
| *.png                  | Saved charts for three node ranges            |
| dijkstra_benchmark.fig | MATLAB figure file                            |

---

## Benchmark Results (Execution Time)

Nodes 2 to 1000
(Insert image here: 2-1000.png)

Nodes 1001 to 5000
(Insert image here: 1001-5000.png)

Nodes 5001 to 10000
(Insert image here: 5001-10000.png)

---

## How to Run

```
python main.py
```

Enter the desired node range when prompted, for example:

```
1000:5000
```
