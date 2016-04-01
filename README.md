Following code is an implementation of Back Propagation algorithm for neural networks
Refer : https://www.willamette.edu/~gorr/classes/cs449/backprop.html to understand

Enter the learning rate, error threshold 

How to use :
# XOR example:

training_sets = [[[0, 0], [0]],[[0, 1], [1]],[[1, 0], [1]],[[1, 1], [0]]]

nn = NeuralNetwork(len(training_sets[0][0]), 2, len(training_sets[0][1]), hidden_layer_bias = 0, output_layer_bias = 0)
