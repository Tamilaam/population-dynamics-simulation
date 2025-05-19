# Population Dynamics and Lotka-Volterra Modeling

This repository contains a course project developed for the lecture **Mathematical Modeling for Biology** at the **University of Milan**.

We explore predator-prey population dynamics using a series of increasingly complex models, starting from the classical Lotka-Volterra system and culminating in a multi-species evolutionary simulation.

---

## Project Overview

### Models Implemented

1. **Classic Lotka-Volterra** – Prey vs Predator dynamics.
2. **Logistic Lotka-Volterra** – Adds carrying capacity to the prey population.
3. **Three-Species Food Chain** – Adds an *uber-predator* preying on the predator.
4. **Bonus: Evolutionary Prey** – A second, evolved prey species is introduced with unidirectional evolution and inter-prey competition.

### Key Features

- System simulations using ODE integration (`scipy.integrate.odeint`)
- Phase plots and time-series visualizations with `matplotlib`
- Numerical fixed point estimation
- Streamplot vector field analysis
- Parameter estimation by fitting the model to real-world-like data

---

## Requirements

- Python 3.7+
- `numpy`, `pandas`, `matplotlib`, `scipy`
