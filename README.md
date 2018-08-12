# Handwritten_Digit_Recognition_NN
A simple handwritten digit recognition using Neural Networks,written in Python  3.
To understand how Neural Networks work please refer to : http://neuralnetworksanddeeplearning.com/chap1.html

Dependencies used: 
NumPy
Gzip
Pickle.


Network.py contains all the source code about the implementation of Schocastic Gradient Desecent and the Network.
MNIST_Loader.py simply loads the MNIST Digit Data and splits it into test,validation and training data.
Deploy.py executes the recognition process,changes can be made to it accordingly.


Uses a 784*30*10 NN architecture,where 784 Input Neurons,30 Hidden Neurons and 10 output neurons(1 neuron for each digit (0-9)).
