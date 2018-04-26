# Handwritten-Digit-Recognition-using-Neural-Networks
In this project I have implemented the backpropagation algorithm to learn the parameters for the neural network.

## Visualizing the data
In the first part of ex4.m, the code will load the data and display it on a 2-dimensional plot by calling the function displayData.
There are 5000 training examples in ex3data1.mat, where each training example is a 20 pixel by 20 pixel grayscale image of the digit. Each pixel is represented by a floating point number indicating the grayscale intensity at that location. The 20 by 20 grid of pixels is \unrolled" into a 400-dimensional vector. Each of these training examples becomes a single row in our data matrix X. This gives us a 5000 by 400 matrix X where every row is a training example for a handwritten digit image.

## Model representation
The neural network has 3 layers { an input layer, a hidden layer and an output layer. Our inputs are pixel values of digit images. Since the images are of size 20 * 20, this gives us 400 input layer units (not counting the extra bias unit which always outputs +1). The
training data will be loaded into the variables X and y by the ex4.m script. You have been provided with a set of network parameters (Theta(1);Theta(2)) already trained. These are stored in ex4weights.mat and will be loaded by ex4.m into Theta1 and Theta2. The parameters have dimensions that are sized for a neural network with 25 units in the second layer and 10 output units (corresponding to the 10 digit classes).

