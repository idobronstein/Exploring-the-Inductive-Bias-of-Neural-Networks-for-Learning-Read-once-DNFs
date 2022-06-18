# Exploring-the-Inductive-Bias-of-Neural-Networks-for-Learning-Read-once-DNFs


### Introduction

Using this code, you can run each one of the following experiments: 
1. Comparison of the performance  of learning read-once DNF using
    - Convex network with small initialization
    - Convex network with large initialization
    - Standard network with Xavier initialization
    - Statistical query algorithm
2. Accuracy of reconstruction of DNF after training a convex network on read-once DNF
3. Plot the weights of trained convex network on read-once DNF

### Files

| File name | Description |
|----------|:-------------:|
| consts.py | Contains all the simulation's parameters |
| convex_network.py | Contains an implementation of the convex network |
| data.py | Contains the read-once DNF data functions and functions to create all the data |
| defs.py | Contains all the imports for external libraries |
| main_comparison.py | Contains the main file of comparison expirement |
| main_plot.py | Contains the main file for plotting a trained network |
| main_reconstruction.py | Contains the main file of reconstruction expirement |
| README.md | This file |
| standard_network.py | Contains an implementation of the standard network |
| statistical_query.py | Contains an implementation of the statistical query algorithm |
| utilities.py | Contains all the functionality of the pruning and reconstruction process |

### How to

All the parameters of the simulation are defined in consts.py.

To run the comparison experiment, run the following command:
python main_comparison.py

To run the reconstruction experiment, run the following command:
python main_reconstruction.py

To plot a trained  convex network, run the following command:
python main_plot.py