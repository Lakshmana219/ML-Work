# Optuna - hyperparameter optimization (HPO)
Optuna, a hyperparameter optimization (HPO) framework designed for machine learning written in Python

The criteria we propose include (1) define-by-run API that allows users to construct the parameter search space dynamically, (2) efficient implementation of both searching and pruning strategies, and (3) easy-to-setup, versatile architecture that can be deployed for various purposes, ranging from scalable distributed computing to light-weight experiment conducted via interactive interface.

In order to prove our point, we will introduce Optuna, an optimization software which is a culmination of our effort in the development of a next generation optimization software. As an optimization software designed with define-by-run principle, Optuna is particularly the first of its kind.

We will present the design-techniques that became necessary in the development of the software that meets the above criteria, and demonstrate the power of our new design through experimental results and real world applications.