kaggle MNIST
================

Learn Julia using kaggle MNIST Challenge

Uses an RBM trained using constrastive divergence to provide intermediary features to a Neural Network training with backprop.

Setup
-----

Install packages ANN, Boltzmann, DataFrames and HDF5;

Usage
-----

1- Configure knobs and filepaths in params.jl

From the same command prompt
2- run train.jl
3- run predict.jl

Current classifier accuracy: 0.96214

Todo
----

1 - Save Neural Net configuration into file.
2 - Improve stats collected + experiment with gadfly for reporting.
3 - improve classifier accuracy (Add convolutional layer + deeper network)
