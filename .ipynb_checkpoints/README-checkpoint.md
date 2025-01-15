## Inexact Catching-Up Algorithm for Sweeping Processes

This repository contains numerical results from our study on the inexact catching-up algorithm for sweeping processes, as presented in the paper https://arxiv.org/abs/2501.04781. 
In this work, we introduce a new concept of approximate projection, which is compatible with various numerical methods for approximating exact projections. This approach is not restricted to strictly remain within the set, allowing for more flexibility in the implementation of the catching-up algorithm.

### Overview
The main contributions of our paper include:

- Development of an inexact version of the catching-up algorithm for sweeping processes.
- Introduction of a new notion of approximate projection with several useful properties.
- Proof of convergence for the inexact catching-up algorithm under three general frameworks: prox-regular moving sets, subsmooth moving sets, and merely closed sets.
- Application to complementarity dynamical systems, particularly electrical circuits with ideal diodes.
- Implementation of the inexact catching-up algorithm using a primal-dual optimization method, which does not necessarily guarantee a feasible point.

Our results not only recover classical existence results from the literature but also provide new insights into the numerical simulation of sweeping processes, with a particular focus on electrical circuits with ideal diodes.

### Numerical Results

The code in this repository implements the inexact catching-up algorithm, applying it to the study of complementarity dynamical systems, specifically focusing on the simulation of electrical circuits with ideal diodes. The numerical experiments presented here demonstrate the algorithm's effectiveness and convergence under different conditions.

### Requirements

To run the code and replicate the results in this repository, you will need:

-Python 3.x
-NumPy
-SciPy
-Matplotlib (for visualizations)

### Citation

@article{paper,
  title={Inexact Catching-Up Algorithm for Sweeping Processes},
  author={Author1, Author2, and Author3},
  journal={arXiv},
  year={2025},
  url={https://arxiv.org/abs/2501.04781}
}
