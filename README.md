# Wormhole Finder

A repository for computing U(1) Euclidean wormhole solutions for axion fields coupled to gravity. The calculations are related to the companion paper arxiv:2009.xxxx (The Axion Quality Problem: Global Symmetry Breaking and Wormholes).

There are 4 main files in this repository for solving the following two cases:

1. U(1) wormholes within Einstein Gravity
  - **u1.m:** this contains the solver functions and implementation for solving Eqs. (xx) - (xx) in the companion paper
  - **run-u1.nb:** this notebook calls the functions in u1.m and sets up the global variable, it then solves for the boundary conditions at infinity and plots the results.
 
2. U(1) wormholes within the axion-dilaton system in String Theory
  - **dilaton.m:** similar to the u1.m file this contains the implementation for the axion-dilaton system
  - **run-dilaton.m:** this runs the functions in dilaton.m and plots the results for the dilaton, radial field and metric function


