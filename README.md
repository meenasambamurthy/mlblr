What is a neural network neuron?
A neuron is a computation unit which consists of two elements, a weight, and an activation function.

What is the use of the learning rate?
Learning rate sets the pace of learning of a neural network. A small LR makes many updates before reaching a minimum loss point, whereas a big one causes drastic updates, enroute to the minimum loss/error. But an optimum LR swiftly reaches the minimum loss/error.
How are weights initialized?
Weights can be randomly initialized but with small values from a Gaussian distribution, so as to provide a starting point of tweaking them. The choice of Gaussian or uniform distribution does not seem to matter very much,  however,it does have a large effect on both the outcome of the optimization procedure and on the ability of the network to generalize.
What is "loss" in a neural network?
it is the function used to evaluate  a set of weights. The weights themselves are a candidate solution, that may minimize the error. When we are minimizing it, we may also call it the cost function, loss function, or error function.
What is the "chain rule" in gradient flow?
The algorithm that is used to effectively train a neural network through a method called chain rule
