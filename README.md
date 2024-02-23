# ERAV2_Assignment 5
## Intro
<p> An algorithm is designed which uses convolution neural network used to recognize patterns in data</p>
## Input Data
1. The training data is imported MNIST dataset comprising of 60,000 images
2. Each input image is resized into 28 x 28 x 1.
3. The training data is divided into 512 batch size.

##Convolutional Layers
<p>  Four layers of convolution layer is used in the architecture. The size of these kernels is a hyper-parameter specified during training of the network architecture.</p>

##Activation Function
<p>The Rectified Linear Activation function (ReLU) is performed after every convolutional layer in the network architecture.</p>
 
 ##Pooling Layer
1.The Max-Pooling operation requires selecting a kernel size of size 2 x 2.
2. Once selected, the operation slides the kernel with stride of 1 over the input while only selecting the largest value at each kernel slice from the input to yield a value for the output. 

##Code File
1. model.py - Contains model architecture
2. utils.py - Contains necessary function
3. S5.ipynb
 
