# Breast-Cancer-prediction-using-ANN

Breast Cancer Wisconsin (Diagnostic) Data Set
Predict whether the cancer is benign or malignant

# Data description

Features are computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. They describe characteristics of the cell nuclei present in the image. n the 3-dimensional space is that described in: [K. P. Bennett and O. L. Mangasarian: "Robust Linear Programming Discrimination of Two Linearly Inseparable Sets", Optimization Methods and Software 1, 1992, 23-34].

This database is also available through the UW CS ftp server: ftp ftp.cs.wisc.edu cd math-prog/cpo-dataset/machine-learn/WDBC/

Also can be found on UCI Machine Learning Repository: https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29

Attribute Information:

1) ID number 

2) Diagnosis (M = malignant, B = benign) 3-32)

Ten real-valued features are computed for each cell nucleus:

a) radius (mean of distances from center to points on the perimeter)

b) texture (standard deviation of gray-scale values)

c) perimeter

d) area

e) smoothness (local variation in radius lengths)

f) compactness (perimeter^2 / area - 1.0)

g) concavity (severity of concave portions of the contour)

h) concave points (number of concave portions of the contour)

i) symmetry

j) fractal dimension ("coastline approximation" - 1)


# What are artificial neural networks?

An artificial neuron network (ANN) is a computational model based on the structure and functions of biological neural networks. Information that flows through the network affects the structure of the ANN because a neural network changes - or learns, in a sense - based on that input and output. ANNs are considered nonlinear statistical data modeling tools where the complex relationships between inputs and outputs are modeled or patterns are found. ANN is also known as a neural network.

A single neuron is known as a perceptron. It consists of a layer of inputs(corresponds to columns of a dataframe). Each input has a weight which controls the magnitude of an input. The summation of the products of these input values and weights is fed to the activation function. Activation functions are really important for a Artificial Neural Network to learn and make sense of something really complicated and Non-linear complex functional mappings between the inputs and response variable.

 ![Unknown-4](https://user-images.githubusercontent.com/98457829/196953428-68fd0791-b7cb-4cde-9491-d99b4dc298ff.png)

# Creating Layers

After importing those libraries, we create the three types of layers:

Input layer

Hidden layer

Output layer


# Compiling and Fitting

Optimizer is chosen as adam for gradient descent.

Binary_crossentropy is the loss function used.

We use sigmoid function in output layer

Sigmoid function is used when dealing with classfication problems with 2 types of results.(Submax function is used for 3 or more classification results)

![Sigmoid Funtion](https://user-images.githubusercontent.com/98457829/196954069-0d170987-453c-41b0-8a65-3c7c17e0440d.png)


# ANN Visualizer of the model

![network](https://user-images.githubusercontent.com/98457829/196955037-a79220ce-778b-40c3-aabe-ef7a10e7675b.png)
