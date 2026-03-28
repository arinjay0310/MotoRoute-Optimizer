# MotoRoute-Optimizer
# Himalayan Trip Simulator 🏍️🏔️

## Overview
The Himalayan Trip Simulator is a lightweight Python program that tests whether a planned road trip is physically and financially possible. By simulating the journey step-by-step, it tracks a motorcycle's fuel gauge and a traveler's wallet to ensure they can safely reach their destination.

## The Problem
When riding through remote high-altitude terrains, missing a fuel stop or overspending early in the trip can lead to being stranded. This tool automates the math, allowing users to verify their itinerary before hitting the road.

## Features
* **Sequential Simulation:** Travels through a programmed list of towns one by one.
* **Dynamic Fuel Tracking:** Drains the fuel tank based on the distance between towns and automatically refills it only when the current location has a fuel station.
* **Budget Monitoring:** Accumulates daily costs (food and stay) and alerts the user if they run out of money.
* **Emergency Stop:** Halts the program immediately if the traveler runs out of gas or exceeds their budget.

## Tech Stack
* **Language:** Python 3.x
* **Core Concepts:** Lists, Dictionaries, For Loops, Conditional Logic

## How to Run the Project
This script requires no external libraries. Anyone with Python installed can run it.

1. Clone or download this repository.
2. Open your terminal or command prompt.
3. Navigate to the folder containing the script.
4. Run the following command:
   ```bash
   python trip_simulator.py
