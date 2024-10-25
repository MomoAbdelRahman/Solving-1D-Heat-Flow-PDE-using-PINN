# Solving-1D-Heat-Flow-PDE-using-PINN
Solving 1D Heat Flow PDE using PINN (Physics Informed Neural Network).

A neural network is made using pytorch where the loss function contains values that indicate how well the current solution fits the PDE, the boundary conditions, and the initial condition. The loss is weighed arbitrarly using hyperparameters that correspond to each of these loss terms. The resulting solution is then tested against a Fourier solution. 
