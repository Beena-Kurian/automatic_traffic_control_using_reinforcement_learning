# Autonomous Traffic Signal Control using Deep Reinforcement Learning

This repository contains all the code and resources needed to implement and run an autonomous traffic signal control system using Deep Q-Learning. The system aims to optimize traffic flow and reduce congestion in simulated urban traffic environments using the SUMO traffic simulation suite.

## Project Structure

The project includes the following files and directories:

- `intersection/`: This directory contains the network definition files, route definitions, and the SUMO configuration files necessary for running the traffic simulations.
- `automatic_traffic_control_using_reinforcement_learning.ipynb`: A Jupyter notebook that outlines the implementation and training of the Deep Q-Learning model.
- `README.md`: This file provides an overview and instructions for running the project.

## Prerequisites

To run the simulations and the learning model, you need to have the following installed:

- Python 3.x
- SUMO (Simulation of Urban Mobility) version 1.19 used 
- Required Python libraries: `numpy`, `tensorflow`, `matplotlib`, `sumolib`, `traci`

## Installation

1. Install SUMO (Simulation of Urban Mobility) according to the instructions on the [official SUMO website](https://sumo.dlr.de/docs/Installing.html).

2. Install the required Python packages:

pip install numpy tensorflow matplotlib sumolib traci

## Models and Plots
The trained models and plots for rewards per episode will be saved in the models_new directory after you run the simulations.

## Authors
Beena Kurian
Kosisochukwu Andrew Ibe
Salman Mahboob

# Acknowledgments
Special thanks to Prof. Mahmoud Nazr for guidance and support throughout the development of this project.
Gratitude to Conestoga College for providing the necessary resources for this project.
