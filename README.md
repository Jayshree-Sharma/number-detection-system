# number-detection-system using MNIST dataset
Feedforward Neural Network for MNIST Digit Classification
A Feedforward Neural Network (FNN) is one of the simplest types of artificial neural networks, where the connections between nodes do not form cycles. When applied to the MNIST dataset, which consists of 70,000 handwritten digit images (60,000 for training and 10,000 for testing), an FNN learns to classify images into one of 10 digit classes (0–9).

Structure of the Model:
Input Layer:

Each MNIST image is 28x28 pixels, flattened into a 784-dimensional input vector.

This serves as the input layer to the network.

Hidden Layers:

The model can have one or more hidden layers, typically using fully connected (dense) layers.

Each layer applies a non-linear activation function, such as ReLU (Rectified Linear Unit), to introduce non-linearity and enable the network to learn complex patterns.

Example: A common architecture might include two hidden layers with 128 and 64 neurons, respectively.

Output Layer:

The output layer has 10 neurons, one for each digit class (0–9).

A softmax activation function is used here to output a probability distribution across the 10 classes.

Training:
The model is trained using supervised learning, where each input image is associated with a ground truth label.

A categorical cross-entropy loss function is commonly used for multi-class classification.

Optimization is typically performed using stochastic gradient descent (SGD) or a variant like Adam optimizer.
