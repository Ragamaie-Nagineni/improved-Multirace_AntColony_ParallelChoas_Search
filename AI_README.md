# Multi-Race Ant Colony Parallel Chaos Search for Path Planning on 3-D Terrain

This project implements the Multi-Race Ant Colony Parallel Chaos Search (MACPCS) algorithm for path planning on 3D terrain, balancing energy consumption and travel distance.

## Abstract

We enhanced traditional Ant Colony Optimization by integrating chaos theory and parallel search with machine learning techniques for adaptive heuristic tuning and predictive pheromone updates. The model simulates realistic terrain using noise functions and visualizes ant behavior in 3D.

## Features

- Terrain generation with elevation data
- Parallel multi-race ant colony exploration
- Chaos-based path diversity
- Energy + distance-based optimization
- Visualization of pheromone maps and paths
- Adaptive ML-based tuning and strategy switching

##How to Run

This project was developed and tested on **Google Colab** using **Python**.

###Steps:

1. Open the Colab Notebook:  
   [Click here to open in Google Colab](https://colab.research.google.com/) *(replace with actual link)*

2. Make sure you're signed in with a Google account.

3. Run each code cell in sequence to:
   - Generate terrain
   - Run the MACPCS algorithm
   - Visualize paths and pheromones

> No local installation is needed. Everything runs in the cloud via Colab.

## Visualization

The project includes:
- 3D terrain maps
- Ant movement trails
- Pheromone heatmaps

##Applications

- Autonomous Navigation  
- Search & Rescue Missions  
- Robotics  
- Drone Path Planning  
- Off-Road Navigation

##Challenges Faced

- Generating realistic 3D terrain with slopes  
- Chaos parameter tuning  
- Long compute times due to high ant population

##Reference

J. Wang, et al., "Multi-Race Ant Colony Parallel Chaos Search Method for Path Planning on 3-D Terrain Considering Energy Consumption and Travel Distance," *IEEE Transactions on Vehicular Technology*, Nov. 2024. DOI: [10.1109/TVT.2024.3417714](https://doi.org/10.1109/TVT.2024.3417714)
