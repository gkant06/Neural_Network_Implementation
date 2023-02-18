# Neural_Network_Implementation

Part 1: Single and two layer MLP

Implementing a neural network from scratch
A neural network with a single layer has been created for a binary classification problem from
scratch. This is a fully-connected architecture. Here, functions for linear map, ReLU activation, loss function (softmax cross entropy) and the
model itself have been defined from scratch including forward pass and back propagation
without the use of standard Pytorch module. The same has been modified to create a neural network with 2 hidden layers to compare results for training and test accuracy and loss. 

Part 2: Pytorch Implementation of a single layer neural network

In this section, a single layer neural network has been implemented using Pytorch. I have used
the ReLU activation function from the torch.nn module, in which it does not need to be built
from scratch. Additionally, used the SGD optimizer from the torch.optim library for optimization
and the Soft Max Cross Entropy loss was used from the torch.nn module. The same has been modified to create a neural network with 2 hidden layers to compare results for training and test accuracy and loss. 
