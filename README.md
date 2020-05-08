# DL-with-PyTorch

PyTorch is a great Deep Learning (DL) library that makes it easy for the user to experiment with DL related concepts such as: CNNs, CUDA, backpropagation, Loss functions, and more.

However, users may come to find that although abstractions of common DL operations make it easy for the user to implement, it may take away meaning from what is actually happening under the hood.

Hence, this introductory tutorial will teach the user how to implement standard Neural Network operations and generalize how to integrate the forward/backward pass to any custom operation using PyTorch

## Framework

The tutorials will build one specified concept at a time. For the specified concept, we will manually implement the operation using PyTorch capabilities, but will sometimes implement other needed operations using PyTorch's inherent capabilities to simplify code. 

### Visualization

After the concept has been defined and implemented, we will make performance visualization where we compare similar alternative operations that the user could potentially make to improve their predictive model

[hiplot](https://github.com/Erick7451/DL-with-PyTorch/blob/master/hiplot/hiplot.html)

### Methodology

The [Linear Layer](https://github.com/Erick7451/DL-with-PyTorch/blob/master/Jupyter_Notebooks/Linear%20Layer.ipynb) tutorial is ***strongly*** encouraged to review first as it presents fundamental DL concepts that will be assumed for the rest of tutorials and also presents standard workflow into how we will train and compare different models.

## Operations

The following are concepts that have been manually implemented on PyTorch

##### Gradient Descent

* Stochastic Gradient Descent
* Newton's Method

##### Linear Operations

* [Linear layer](https://github.com/Erick7451/DL-with-PyTorch/blob/master/Jupyter_Notebooks/Linear%20Layer.ipynb)
* Convolutional Layer
* Spectral Convolution

##### Activation Methods

* [ReLU](https://github.com/Erick7451/DL-with-PyTorch/blob/master/Jupyter_Notebooks/ReLU.ipynb)

##### Analyzing Distinct Data Domains

* Spatial data
* Non-Euclidean data

##### Architectures
* [Logistic Regression](https://github.com/Erick7451/DL-with-PyTorch/blob/master/Jupyter_Notebooks/logistic_regression.ipynb)

