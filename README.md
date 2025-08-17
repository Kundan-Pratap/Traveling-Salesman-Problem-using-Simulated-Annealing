# Simulated Annealing for the Traveling Salesman Problem (TSP)

This repository contains a Jupyter Notebook implementing the **Simulated Annealing** algorithm to solve the **Traveling Salesman Problem (TSP)** for 11 cities, with extensions and discussions for larger instances (e.g., 48 cities).  

The TSP is an NP-hard optimization problem where the goal is to find the shortest possible route visiting each city exactly once and returning to the starting city.



## Description

The Traveling Salesman Problem (TSP) involves a salesperson visiting a set of cities and returning home while minimizing the total distance traveled. This notebook uses **Simulated Annealing**—a probabilistic technique inspired by annealing in metallurgy—to approximate the optimal solution.

**Key features:**

- Distance matrix for 11 cities (numbered 0–10)  
- Random initial tour generation  
- Neighbor generation via city swaps  
- Acceptance probability to escape local optima  
- Cooling schedule to gradually reduce exploration  
- Plots of cost function evolution for different initial temperatures (`1.0`, `10.0`, `100.0`)  

