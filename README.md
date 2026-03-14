# Hopfield-Network-associative-memory-analysis

A mathematical and computational exploration of associative memory using the Hopfield network.
This project implements a Hopfield network from scratch in Python and investigates the theoretical properties of attractor-based neural memory systems through simulation experiments.
The goal is to connect linear algebra, dynamical systems intuition, and neural computation by studying how recurrent neural networks store and retrieve information.

# Project Overview

Hopfield networks are classical models of associative memory in computational neuroscience. Stored memory patterns correspond to stable attractor states of the network dynamics. When presented with a noisy or incomplete version of a pattern, the network converges toward the closest stored memory through energy minimization.

This project studies several important properties of Hopfield networks:

- Hebbian weight construction
- Energy-based network dynamics
- Attractor stability under noise
- Storage capacity scaling
- Memory interference effects

All simulations are implemented using NumPy and visualized using Matplotlib.

# Features Implemented

The project includes the following components:

## Core Hopfield Network Implementation

- Random bipolar pattern generation
- Hebbian weight matrix construction
- Hopfield energy function
- Asynchronous neuron update rule
- Network recall until convergence

## Mathematical Experiments

The code also investigates several theoretical properties of Hopfield networks.

## Energy Monotonicity Verification

Numerically verifies that the Hopfield energy function does not increase under asynchronous updates.

## Basin of Attraction Analysis

Examines how noise affects the network's ability to retrieve stored patterns.

## Storage Capacity Experiment

Studies how recall accuracy changes as the number of stored patterns increases, comparing results with the classical Hopfield capacity estimate.

## Sequential Memory Interference

Investigates how adding additional patterns affects recall of previously stored memories.

# Mathematical Concepts Demonstrated

This project illustrates several key ideas from theoretical neuroscience:

- Hebbian learning
- Energy-based neural networks
- Attractor dynamics
- Basin of attraction
- Storage capacity scaling
- Memory interference in recurrent networks


  
