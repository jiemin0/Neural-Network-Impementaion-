# Neural-Network-Impementaion-
This file including one fully connected Neural Network and one CNN over MNIST dataset.

### Amulti-layer fully connected network:
*Input: 1-channel input, size 28x28
* Keep batch size as 32.
* Fully connected layer 1: Input with bias; output - 128
* ReLu Layer
* Fully connected layer 2: input - 128; output - 10
* Softmax layer
* Use cross entropy as loss function
* Use SGD as optimizer.

### A convolutional neural network with the following specifications.
* Input: 1-channel input, size 28x28
* Keep batch size as 32.
* Convolution layer: Convolution kernel size is (3, 3) with stride as 1. Input channels
- 1; Output channels - 20
* Max-pool: 2x2 max pool
* ReLu Layer
* Flatten input for feed to fully connected layers
* Fully connected layer 1: 
attened input with bias; output - 128
* ReLu Layer
* Fully connected layer 2: input - 128; output - 10
* Use cross entropy as loss function
* Use SGD as optimizer.
