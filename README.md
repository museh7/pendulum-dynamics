# Pendulum dynamics

A learning project exploring pendulum mechanics, numerical simulation and, eventually, machine-learning forecasts. Built in Python using a Jupyter notebook.

## Physics and numerical assumptions

- Point masses, massless rigid rods, a fixed pivot and no friction or air resistance.
- SI units: kilograms, metres, seconds and radians.
- Both double-pendulum angles are measured from vertically downwards, not relative to each other.
- The simple simulation uses the lowest point as zero potential energy; the double-pendulum derivation uses the fixed pivot. Constant energy offsets do not change the dynamics.
- Semi-implicit Euler has numerical energy error. A nearly constant energy plot is a useful check, not proof of an accurate trajectory. Timestep-convergence checks remain to be added.

## Files

- `main.ipynb`: code, plots and mathematical derivations.
- `environment.yml`: Anaconda environment.
- `requirements.txt`: dependencies for other Python environments.

