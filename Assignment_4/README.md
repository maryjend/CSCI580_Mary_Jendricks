# Assignment 4 – Simulated Annealing and Genetic Algorithms for TSP

**Course:** CSCI 580
**Student:** Mary Jendricks
**Assignment:** A4 – Simulated Annealing (SA) and Genetic Algorithms (GA)

## Overview

This project implements two metaheuristic optimization algorithms to solve the **Traveling Salesman Problem (TSP)**:

* Simulated Annealing (SA)
* Genetic Algorithm (GA)

Both algorithms attempt to improve a **Nearest Neighbor (NN)** baseline tour by minimizing total tour length.

The implementation and experiments are contained in a Jupyter Notebook.

---

## Files in This Folder

| File                                      | Description                                                  |
| ----------------------------------------- | ------------------------------------------------------------ |
| `TSP_SA_and_GA_Assignment_Skeleton.ipynb` | Main notebook containing all implementations and experiments |
| `README.md`                               | Instructions for running the code                            |
| `report.pdf`                              | Written report containing experimental results and analysis  |

---

## Requirements

The code requires Python 3 and the following library:

* matplotlib

Install matplotlib if needed:

```
pip install matplotlib
```

---

## Running the Code

1. Open the notebook:

```
jupyter notebook
```

2. Open the file:

```
TSP_SA_and_GA_Assignment_Skeleton.ipynb
```

3. Run all cells in order:

```
Kernel → Restart & Run All
```

---

## What the Notebook Does

Running the notebook will:

1. Generate a random set of cities
2. Compute a **Nearest Neighbor baseline tour**
3. Improve the tour using **Simulated Annealing**
4. Improve the tour using a **Genetic Algorithm**
5. Produce plots showing algorithm performance and convergence behavior

---

## Outputs

The notebook generates several visualizations including:

* Nearest Neighbor tour visualization
* SA best-so-far tour length over time
* GA best-per-generation tour length
* GA population average length
* SA accepted vs rejected ΔE histograms
* SA vs GA comparison plots

These outputs are used to analyze the algorithms and are discussed in the accompanying **report.pdf**.

---

## Author

Mary Jendricks
California State University, Chico
