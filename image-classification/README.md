## Image Classification

Classify images from the [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) dataset using a convolutional neural network. This CNN (ConvNet) will be implemented using Googles Tensorflow, which comes preinstalled (along with other applications) with bitfusion.io.

Will be powered by [bitfusion.io](https://aws.amazon.com/marketplace/pp/B01EYKBEQ0) on AWS to leverage Nvidia GPUs as opposed to CPUs. CPUs are better at working with complex computations, where as GPUs have more through-put and can get more work done in the same amount of time (better for NNs that have lots of data to process or that include many hidden layers).

The input data will be preprocessed. Specifically, the image data will be normalized with values in the range of 0 to 1. The lables will be preprocessed using one-hot encoding, which will be one of the inputs for our loss function.

Cross-entropy will be used as the loss function for backpropagation on this Convoluation Neural Net (CNN). Because cross-entropy requires two probability distributions as input, and as we already have one probabilty distribution from the one-hot enocoded (one-hot vector) label data. The other probability distribution will be created from the last layers (output node) activation function. The activation function used on this last layer will be the SoftMax function.
