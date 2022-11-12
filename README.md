# gradient-descent-and-blueprint-of-neural-network-using-pytorch
## Xt+1= xt- η∆xt
 Gradient descent is an algorithm used in linear regression because of the computational complexity. 
 The general mathematical formula for gradient descent is xt+1= xt- η∆xt, with η representing the
 learning rate and ∆xt the direction of descent. 
## summary 
 We created a neural network with hidden layers using ReLU activation function to introduce non-linearity 
 into the model, allowing it to learn more complex relationships between the inputs and outputs(class probs).
 We also defined some utilities like get_default_device, to_devce and DeviceDataLoader to leverage GPU if 
 available, by moving the input data and model parameters to the appropriate device. We also created a fit 
 function and all utilised the pytorch implementations.
