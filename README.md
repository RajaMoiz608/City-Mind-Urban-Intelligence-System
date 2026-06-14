# CityMind – Urban Intelligence System

## Overview

CityMind is an AI-powered urban intelligence and smart city simulation platform designed to solve complex city-planning and emergency-management challenges. The project integrates multiple Artificial Intelligence techniques, graph algorithms, optimization methods, and machine learning models into a unified city-wide decision support system.

The system operates on a shared graph-based city architecture where all modules interact with the same dynamic environment, enabling real-time updates and intelligent decision-making.

## Key Features

### 1. City Layout Planning

* Constraint Satisfaction Problem (CSP) based city zoning
* Backtracking Search
* Forward Checking
* AC-3 Arc Consistency
* Min-Conflicts fallback for near-optimal solutions

### 2. Road Network Optimization

* Minimum Spanning Tree (MST) generation using Kruskal's Algorithm
* Road cost minimization
* Network redundancy enhancement using edge-disjoint path analysis

### 3. Ambulance Placement Optimization

* Genetic Algorithm based optimization
* Tournament Selection
* Crossover and Mutation operations
* Elitism strategy
* Coverage and response-time minimization

### 4. Dynamic Emergency Routing

* A* Search Algorithm
* Manhattan Distance Heuristic
* Real-time route replanning
* Dynamic response to blocked roads and emergencies

### 5. Crime Risk Prediction

* K-Means Clustering
* Random Forest Classification
* Synthetic crime data generation
* Risk-aware city analysis
* Dynamic graph cost updates based on predicted risk

## System Architecture

The project uses a shared **CityGraph** structure where:

* Nodes represent city locations
* Edges represent roads
* Risk levels influence travel costs
* Road blockages instantly affect routing
* All AI modules operate on the same city state

This architecture ensures real-time synchronization between planning, optimization, and prediction components.

## Technologies Used

* Python 3
* Pygame
* NumPy
* Graph Algorithms
* Machine Learning
* Evolutionary Computing
* Constraint Satisfaction Techniques

## Algorithms Implemented

| Challenge               | Algorithm                                 |
| ----------------------- | ----------------------------------------- |
| City Layout Planning    | CSP + Backtracking + AC-3 + Min-Conflicts |
| Road Optimization       | Kruskal MST + Redundancy Augmentation     |
| Ambulance Placement     | Genetic Algorithm                         |
| Emergency Routing       | A* Search                                 |
| Neighborhood Clustering | K-Means                                   |
| Crime Prediction        | Random Forest                             |

## Visualization

The project includes an interactive graphical interface featuring:

* Smart City Grid Visualization
* Road Network View
* Ambulance Coverage Analysis
* Crime Risk Heatmaps
* Real-Time Event Logs
* Dynamic Emergency Simulation

## Project Goals

* Optimize urban infrastructure planning
* Improve emergency response efficiency
* Predict and analyze crime risk patterns
* Enable intelligent decision-making in smart cities
* Demonstrate practical applications of AI in urban environments

## Academic Context

This project was developed as an Artificial Intelligence semester project and demonstrates the integration of multiple AI paradigms, including:

* Constraint Satisfaction
* Graph Search
* Evolutionary Algorithms
* Machine Learning
* Intelligent Decision Support Systems

## Future Enhancements

* Reinforcement Learning for adaptive traffic control
* Real-time GIS integration
* Multi-agent emergency coordination
* Live traffic simulation
* Deep Learning-based risk prediction

  ## Team Members

This project was developed by:

- Moiz Raja - GitHub: https://github.com/RajaMoiz608
- Rehan Ayub 
- Malhan Bin Faisal 

## License

This project is developed for educational and research purposes.
