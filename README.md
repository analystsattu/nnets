# nnets

Here we implement a single layer neural network (NN) and a multi-layer nueral network (NN) from scratch in Python using Numpy. We compare the performance of this NN with a convolutional neural network made using the Keras library. We train the NNs to perform image classification on the Fashion-MNIST dataset.



**Dataset-**
We try to classify the Fashion-MNIST dataset using the NNs. This dataset consists of 70,000 grayscale images clothing of size 28x28. Each image in the datset belongs to one of the 10 categories shown below- 


![Image of Fashion dataset](https://github.com/analystsattu/nnets/blob/master/img/dataset.png)

The images are flattened to 784x1 for the muti-layer and single layer NNs but fed as is to the CNN.

**Architecture-**
- The single layer NN consists of 1 hidden layer with 50 neurons. The input layer has 784 neurons each corresponding to a pixel in the image and the output layer has 10 neurons, each for an output class.

- The multi-layer NN has 2 hidden layers. The first hidden layer has 50 neurons whereas the second layer has 40 neurons. The input and output layers remain the same as the single layer NN.

- The Keras based CNN has 1 convolutional layer and 1 fully connected layer. The convolution filter has size 3x3 and consists of 32 channels. The activation function of this convolutional layer is ‘relu’. The output of this convolutional layer is connected to a fully connected layer of with 16 nodes. The activation of this layer is ‘sigmoid’.


The performance of the 3 networks are shown in the self explanatory jupyter notebook.
