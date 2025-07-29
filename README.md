# Brownian-Motion-Stock-Simulation
This repository contains a Python-based implementation of a Monte Carlo simulation to model future stock price trajectories using the Geometric Brownian Motion (GBM) framework. It is designed to simulate a range of potential outcomes by incorporating both deterministic trends and stochastic variability over a chosen time horizon.

🔧 Key Features
Models stock price dynamics using the GBM model

Customizable inputs:
Mean daily return
Volatility
Initial price
Number of simulations
Time horizon (in trading days)
Visualizes all simulated paths for comparison and analysis

📊 Default Simulation Parameters
Parameter	Value
Initial Stock Price	$10
Mean Daily Return (μ)	0.05% (0.0005)
Daily Volatility (σ)	1% (0.01)
Number of Paths	100
Trading Days	2,500

🧱 Requirements
Python 3.x
NumPy
Matplotlib
