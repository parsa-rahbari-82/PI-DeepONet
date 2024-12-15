#PI-DeepONet: Physics-Informed Deep Operator Network

This project implements a Physics-Informed Deep Operator Network (PI-DeepONet) to solve and analyze parametric partial differential equations (PDEs). The framework includes a Multi-Layer Perceptron (MLP) architecture for the branch and trunk networks, and supports different types of PDEs like the Fisher equation, Richards equation, and their variants.
##Folder Structure
MeshData/: Initially empty. This folder is populated with dynamically generated mesh data during the training and simulation process.
Data/: Contains the simulation data files (e.g., .mat files) used as inputs for the model.
PI_DeepONet/: Main codebase for implementing and training the PI-DeepONet framework.                                                                               ###Dataset Preparation
Place the simulation data files (e.g., U_total_x.mat) into the Data/ folder. These files contain the required inputs for training.
The MeshData/ folder will automatically populate with generated mesh files during training. The script dynamically generates triangular or circular meshes based on the dataset.
