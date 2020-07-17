## Backpropagation

### Objective: Write your own implementation of the backpropagation algorithm for training a neural network on mnist data
For this coursework you are required to write your own implementation of the backpropagation algorithm for training a neural network. You are required to do this assignment in the Python (Python version 3) programming language. Do not use any audodiff toolboxes (TensorFlow, Keras, PyTorch, etc) - you are allowed to use only numpy like libraries (numpy, pandas, etc). 

The goal of this assignment is to label images of 10 handwritten digits of “zero”, “one”,...,“nine”. The images are 28 by 28 in size (MNIST dataset), which we will be represented as a vector x of dimension 784 by listing all the pixel values in raster scan order. The labels are 0,1,2,...,9 corresponding to 10 classes as written in the image. There are 3000 training cases, containing 300 examples of each of 10 classes.
