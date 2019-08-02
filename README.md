# Fashion_MNIST-classification-with-CNNs

This project is a convolutional neural network solution to a Computer Vision problem of classifying 10 different fashion garments.

This is my first implementation of a neural network and I have used a 3 layered CNN with Batch Normalisation, Uniform Xavier weights and MaxPooling followed by a Fully connected layer. Python packages Pytorch, TorchVision, Matplotlib and Numpy were used.

Dataset was sourced from https://github.com/zalandoresearch/fashion-mnist.git . Due to the constraints of Github, two files (fashion-mnist_train and train-images-idx3-ubyte) could not be uploaded - they can be found at https://zalando-research/fashionmnist/data. Once downloaded, they should be placed in the same directory as the rest of the files.

Neural Network was created using 60000 training examples, and is tested on 10000 examples.
I got an Accuracy of 90.6 % after 5000 iterations using the following Program Architecture -

Convolutional Layer 1 with output feature map 16 and 5*5 kernel ReLU Activation MaxPooling 1 Uniform Xavier Weights and BatchNormalisation 1

Convolutional Layer 2 with output feature map 32 and 5*5 kernel ReLU Activation MaxPooling 2 Uniform Xavier Weights and BatchNormalisation 2

Convolutional Layer 3 with output feature map 64 and 5*5 kernel ReLU Activation MaxPooling 3 Uniform Xavier Weights and BatchNormalisation 3

Fully Connected Layer.

![accuracy](https://user-images.githubusercontent.com/39323227/62389518-a416ae00-b57d-11e9-99e7-9103d6970776.JPG)
