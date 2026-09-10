# 🏫 Smart Campus Navigation & Emergency Route Management System

An interactive browser-based campus navigation and emergency route management system that demonstrates the practical use of fundamental data structures and algorithms including Graphs, Dijkstra's Shortest Path Algorithm, Binary Min-Heap, HashMap, Queue, and Stack.

The system provides an interactive visualization of campus routes, calculates shortest paths between locations, manages navigation history and incoming requests, and provides dedicated emergency routing to nearby medical and security facilities.

---

## 📌 Overview

The Smart Campus Navigation & Emergency Route Management System is an interactive web application designed to demonstrate how data structures and algorithms can be applied to a real-world campus navigation problem.

The campus is represented as a weighted graph where:

- Campus locations are represented as nodes.
- Roads between locations are represented as weighted edges.
- Edge weights represent estimated travel distances.
- Dijkstra's Algorithm calculates the shortest route between two locations.

The project goes beyond simply displaying a shortest path. It also provides an interactive visualization of the internal data structures used by the system.

Users can inspect:

- Campus graph structure
- HashMap buckets
- Adjacency lists
- Binary Min-Heap operations
- FIFO request queue
- LIFO navigation stack
- Dijkstra's algorithm execution
- Emergency route calculations

The application is completely browser-based and implemented in a single HTML file containing the interface, styling, data structures, algorithms, and application logic.

---

# 🎯 Objectives

The main objectives of this project are:

- Build an interactive campus navigation system.
- Represent campus locations using a weighted graph.
- Calculate shortest paths using Dijkstra's Algorithm.
- Implement a custom Binary Min-Heap instead of relying on a built-in priority queue.
- Implement a custom HashMap for mapping location names to node identifiers.
- Use a Queue to manage incoming navigation/service requests.
- Use a Stack to maintain navigation search history.
- Provide emergency routing to nearby medical and security facilities.
- Visually demonstrate how the underlying algorithms and data structures work.
- Create an intuitive interface for interacting with the simulated campus network.

---

# ✨ Key Features

## 🗺️ 1. Interactive Campus Graph

The application represents a campus as a graph containing multiple locations and connecting roads.

Example campus locations include:

- Hostel Blocks
- Central Library
- Academic Complex
- Main Cafeteria
- Health Center
- Sports Arena
- Silver Jubilee Hall
- Central Security Office
- Main Campus Gate
- Admin Block
- Science Research Hub

Each location is represented as a graph node and roads are represented as weighted edges.

---

## 🧭 2. Shortest Path Navigation

Users can select a starting location and destination.

The system then calculates the shortest available route between them using Dijkstra's Algorithm.

The basic process is:

```text
Select Starting Point
        ↓
Select Destination
        ↓
Build / Access Campus Graph
        ↓
Run Dijkstra's Algorithm
        ↓
Calculate Minimum Distance
        ↓
Reconstruct Shortest Path
        ↓
Display Route
