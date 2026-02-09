# Network-Routing-System-Algorithm
A Java based implementation of routing system and the Network protocols .
# Network Routing Simulation 🌐

![Java](https://img.shields.io/badge/Language-Java-red) ![Network](https://img.shields.io/badge/Concept-Routing%20Algorithms-blue) ![Status](https://img.shields.io/badge/Status-Educational-green)

A Java application that simulates network packet routing between nodes. This project demonstrates how routers determine the most efficient path for data transmission using graph theory algorithms, mimicking real-world protocols like **OSPF (Open Shortest Path First)**.

## 📡 Project Overview
Understanding how data packets traverse a network is fundamental to  **Network Engineering** . This project builds a virtual network topology where:
* **Nodes** represent Routers/Computers.
* **Edges** represent Links (Cables/Connections) with specific costs (latency/bandwidth).
* The system calculates the shortest path from Source to Destination to ensure efficient data delivery.

## 🛠️ Technical Implementation
This project applies core Computer Science concepts to Networking:

### 1. Graph Theory & Algorithms
* Implemented **Dijkstra’s Algorithm** (or Bellman-Ford, depending on your code) to find the shortest path in a weighted graph.
* Used **Priority Queues** and **HashMaps** to optimize the pathfinding process ($O(E + V \log V)$ complexity).

### 2. Network Simulation
* **Topology Design:** Allows dynamic creation of nodes and links to simulate different network structures (Mesh, Star, etc.).
* **Cost Analysis:** Simulates "Link Cost" based on distance or congestion, similar to how OSPF metrics work in real routers.
* **Packet Flow:** Visualizes the specific path a packet takes through the network hops.
## 🚀 How to Run
1. Clone the repository and run the tester :
   ```bash
   git clone [https://github.com/Yasir](https://github.com/Yasir)[Soyadın]/Network-Routing-Sim.git
