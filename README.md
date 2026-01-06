# Citadel: Build the Algorithmic Black Box

## Project Overview
This repository hosts the development of an **Algorithmic Black Box**, a project focused on building a realistic market simulator and algorithmic trading engine from scratch. The project spans multiple weeks, covering market microstructure fundamentals, matching engine implementation, and trading strategy simulation.

---

## Repository Structure

The project is organized sequentially by week, with each folder containing the relevant Jupyter Notebooks, analysis, and documentation.

### [Week 0: Market Microstructure Fundamentals](./Week%200)
**Focus:** Data Analysis & Order Book Dynamics
* Introduction to financial market data.
* Analysis of limit order books (LOB) and trade execution mechanisms.
* Exploratory data analysis on provided market datasets.

### [Week 1: Building the Core Engine](./Week%201)
**Focus:** Matching Engine & Simulator Architecture
* **Limit Order Book (LOB) Implementation:** Logic for handling buy/sell orders, order cancellation, and modifications.
* **Matching Algorithm:** Implementation of Price-Time priority matching.
* **Architecture Design:**
  
  ![Architecture Diagram](./Week%201/Architecture%20diagram.png)

* **Documentation:**
  * 📄 [**How my simulator mimics a real engine**](./Week%201/How_my_simulator_mimics_a_real_engine.pdf) – A detailed analysis of the simulator's validity and design choices compared to real-world exchange engines.

### [Week 2: Simulation & Strategy (In Progress)](./Week2)
**Focus:** Integration & Testing 
* Initial integration of the matching engine with trading agents.
* Testing the simulator environment with sample order flows.
* Setting up the framework for backtesting algorithmic strategies.

---

## Key Features

* **Realistic Matching Engine:** Simulates core exchange functionality including order matching, partial fills, and queue position.
* **Order Book Management:** Efficient data structures to maintain the state of the LOB.
* **Market Simulation:** Replicates market latency and microstructure effects as detailed in the architecture analysis.


