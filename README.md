# Water Supply Management System

This project was conducted in the **second year, second semester** as part of our Algorithm Design course. The goal was to develop a system that manages the water supply using **graphs** to model and analyze the network of cities, reservoirs, and pumping stations.

## Overview

In this project, we built a water supply management system in **C++** that models the water distribution network as a graph. The system allows for the efficient management and analysis of water flow between cities, reservoirs, and pumping stations. It implements various algorithms, including the Edmonds-Karp algorithm, to evaluate and optimize the water supply, ensuring that the demand is met across different parts of the network.

## Features

### Key Features

- **Graph-Based Water Supply System**

  - Models the water supply system as a graph, where vertices represent cities, reservoirs, and pumping stations, and edges represent pipelines.

- **Data Management**

  - Loads and stores information about cities, stations, reservoirs, and pipes from CSV files into hash tables and graph structures.

- **Water Flow Analysis**

  - Evaluates the impact of removing reservoirs or pumping stations on the overall water supply system.
  - Uses the Edmonds-Karp algorithm to calculate the maximum flow between any two points in the network.
  - Checks whether cities receive sufficient water based on their demand and the flow through the network.

- **Optimization and Balancing**

  - Analyzes metrics such as average, variance, and maximum differences between pipeline capacity and flow.
  - Balances the flow across the network to optimize water distribution and minimize variance.

- **Fault Tolerance and Maintenance**

  - Identifies the cities most affected by the failure or removal of pipelines and pumping stations.
  - Periodic maintenance analysis to ensure the stability of the water supply system.

- **Result Storage**
  - Saves the calculated flows and other metrics associated with each city into a CSV file for further analysis.
