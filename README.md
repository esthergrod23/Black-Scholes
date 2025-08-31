# Black-Scholes
This project builds the Black–Scholes option pricing model from scratch — starting from stochastic calculus and the lognormal assumption, deriving the PDE, and reaching the closed-form solution for European calls and puts.

The repository includes:

Step-by-step derivations (with LaTeX) in Jupyter notebooks.

Closed-form implementation of call/put pricing and Greeks (Δ, Γ, Vega, Θ, ρ).

Monte Carlo simulation under the risk-neutral measure with variance reduction.

Finite-difference PDE solvers (explicit, implicit, Crank–Nicolson).

Interactive visualizations (ipywidgets / matplotlib / plotly).

Unit tests to check put–call parity, numerical accuracy, and Monte Carlo convergence.

Continuous integration (GitHub Actions).

The goal is to provide a learning-friendly and fully documented implementation: every formula is derived, coded, and validated step by step.
