# Learning Group Structure and Disentangled Representations of Dynamical Environments

This repository contains notebooks that can be used to reproduce the experiments in our paper "Learning Group Structure and Disentangled Representations of Dynamical Environments"

# Requirements

In addition to standard packages found in most python distributions (numpy, matplotlib, etc.), this code requires pytorch.

# Running experiments

Each experimental section in our paper corresponds to one of the notebooks in this repository. Except for predictive-performance, these are self-contained. predictive-performance calls on functions defined within the src folder. Specifically, 

- grid-world corresponds to the experiments in sections 5.1 and 5.2
- sphere_world_colors corrsponds to the experiments in section 5.3
- sphere_world  corrsponds to the experiments in section 5.4
- predictive_performance  corrsponds to the experiments in section 5.5

Running the notebooks will reproduce the experimental results shown in our work. Some differences may however appear due to different initial random seeds.
