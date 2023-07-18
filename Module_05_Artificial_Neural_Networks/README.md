# Artificial Neural Networks

## Topics covered in today's module
* Introduction to Neural Networks
* Hyperparameters
* Forward Pass
* Backpropagation
* Computing accuracy

## Main takeaways from doing today's assignment
Layer and Parameters Initialization: this is a really important part for deep networks, if this part is done incorrectly it could lead to exploding or vanishing weights and gradients. And the deeper the network the harder it is to keep the values at a reasonable value. 

I learned about the purpose of multiplying sqrt(1/dimension of a layer). During weight initialization we multiply by the sqrt(1/dimension of a layer) to control the scale of the initial weights in a neural network. When we do this the goal is to scale the weights so that the average magnitude of the inputs and outputs of the layer remains almost the same, because the variance of the inputs and outputs should stay the same throughout the network.

np.random.randn(x,y): this function creates a matrix of random numbers that are drawn from a standard normal distribution with mean 0 and variance 1. Where x and y represent the dimensions of the matrix.

Activation Functions: another important part of neural networks is the activation functions, they help with modeling the non-linearity of the input data. They have the following properties: non-linear, injective, differentiable and continuous. 

Forward Pass: It is used for prediction and generating loss for the backward pass. There are two steps in a forward pass or forward propagation, these are:
  Matrix multiply the input values from the previous layer with the weight the relate the input layer and the hidden layer.
  Finally, apply the activation function to the product.

Backward Pass: Is in this part where the model gets trained.  It uses the prediction from the forward pass and then uses the backpropagation algorithm to change the weights of the neural net. When looking on how the weight are changed it is done backwards, changing each one with the one before it, this is repeated until we get to the first one. 

I learned about the changes that we have to make when we change the dimensionality of the layers and the number of layers.

## Challenging, interesting, or exciting aspects of today's assignment

What I found the most challenging was the initialization of the layer and parameters, it took me some time to understand, but I still have to do some more research on it, because this is a very important part when working with deep learning, something that I find interesting and exciting when working with it.

## Additional resources used 
I used chatGPT to look for definition, check for errors in codes and for grammatical errors.

I used an article titled "How to initialize deep neural networks? Xavier and Kaiming initialization" by Pierre Ouannes to learn about the initialization and for question 1. (link: https://pouannes.github.io/blog/initialization/)

I used the page GeeksforGeeks to read about the numpy,random.randn(). (link: https://www.geeksforgeeks.org/numpy-random-randn-python/) 

I used TensorFlow.org to read about the difference in loss functions and accuracy metric between sigmoid and SoftMax. (links: https://www.tensorflow.org/api_docs/python/tf/keras/losses/CategoricalCrossentropy and https://www.tensorflow.org/api_docs/python/tf/keras/metrics/CategoricalAccuracy) 

Finally an article titled "Wondering why do you subtract Gradient in a Gradient Descent Algorithm?" by Mayank Mishra to read about why do we substract values from weights rather than add. (link: https://towardsdatascience.com/wondering-why-do-you-subtract-gradient-in-a-gradient-descent-algorithm-9b5aabdf8150) 


