# Wormhole Finder

A repository for computing U(1) Euclidean wormhole solutions for axion fields coupled to gravity. The calculations are related to the companion paper [2009.03917](https://arxiv.org/abs/2009.03917) (The Axion Quality Problem: Global Symmetry Breaking and Wormholes).

There are 4 main files in this repository for solving the following two cases:

1. U(1) wormholes within Einstein Gravity
  - **u1.m:** this contains the solver functions and implementation for solving the relevant equations in the companion paper (Eqs. (14) - (16))
  - **run-u1.nb:** this notebook calls the functions in u1.m and sets up the global variable, it then solves for the boundary conditions at infinity and plots the results.
 
2. U(1) wormholes within the axion-dilaton system in String Theory
  - **dilaton.m:** similar to the u1.m file this contains the implementation for the axion-dilaton system (Eqs. (35) - (38))
  - **run-dilaton.nb:** this runs the functions in dilaton.m and plots the results for the dilaton, radial field and metric function

Note: a very similar scheme can be written to solve the U(1) x U(1) case, but the initial condition solver is less automatic than in the U(1) case where a simple bisection method is efficient. As such, we do not include it in the illustrative examples given here.

