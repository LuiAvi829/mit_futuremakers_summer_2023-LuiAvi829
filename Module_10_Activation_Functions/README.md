# Activation Functions

## Topics covered in today's module
* Introduction to Sigmoid, Tanh, ReLU
* Visualizing how ReLU affects the feature maps
* Vanishing and exploding gradients
* Dying ReLU problem
* Advanced activation functions: Swish, GeLU, SeLU

## Main takeaways from doing today's assignment
Sigmoid: transforms input values into a range between 0 and 1, commonly utilized in binary classification tasks to introduce non-linearity.

Tanh (Hyperbolic Tangent): maps input values to a range between -1 and 1, offering stronger non-linearity compared to the sigmoid function.

ReLU (Rectified Linear Unit): ReLU sets negative input values to zero while keeping positive values unchanged, widely favored for its simplicity and ability to mitigate the vanishing gradient issue.

Leaky ReLU: Leaky ReLU is a variant of ReLU that incorporates a small positive slope for negative input values, addressing the problem of "dying ReLU" (it occurs when when a large number of neurons consistently output zero and don't contribute to the learning process).

ELU (Exponential Linear Unit): activation function that smoothly blends ReLU and exponential functions, providing both non-linearity and negative support.

Swish: activation function that applies a sigmoid-like function to the input, yielding a smooth and non-monotonic activation response.

GeLU (Gaussian Error Linear Unit): approximates the Gaussian cumulative distribution function, resulting in a smooth non-linear activation.

SeLU (Scaled Exponential Linear Unit): self-normalizing activation function that maintains specific properties during training, leading to improved convergence and performance.

## Challenging, interesting, or exciting aspects of today's assignment
What I found the most exciting was implementing each activation function through coding, and understanding their distinct characteristics and then comparing their functions.

## Additional resources used 
chatGPT for code errors, grammatical errors and some definitions

Article by Himanshu Rawlani titled "Visual Interpretability for Convolutional Neural Networks" (link: https://towardsdatascience.com/visual-interpretability-for-convolutional-neural-networks-2453856210ce)

Article by Jason Brownlee titled "A Gentle Introduction to Pooling Layers for Convolutional Neural Networks" (link: https://machinelearningmastery.com/pooling-layers-for-convolutional-neural-networks/)

Article by Keshav titled "Leaky ReLU Activation Function [with python code]" (link: https://vidyasheela.com/post/leaky-relu-activation-function-with-python-code) 

Article by Afaf Athar titled "Activation Functions, Optimization Techniques, and Loss Functions" (link: https://medium.com/analytics-vidhya/activation-functions-optimization-techniques-and-loss-functions-75a0eea0bc31)
