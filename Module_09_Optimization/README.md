# Optimization

## Main takeaways from doing today's assignment
Optimization: process process of adjusting the weights and biases of a model during training with the purpose of minimizing the difference between the predicted outputs and the targets(loss).

Gradient Descent: the most basic training algorithm in deep learning. It uses the direction of steepest descent of the loss function to adjust the parameters of the model. By doing this it helps with performance and accuracy when learning.

Batch Gradient Descent: optimization algorithm that changes the model's parameters by computing the gradient of the loss function over the entire training dataset. 

Stochastic Gradient Descent: optimization algorithm that randomly selects a single sample of training data in each iteration, it then calculates the gradient of the loss function on that sample, and then adjusts the parameters in the direction that minimizes the loss. This method is much more efficient and faster the batch gradient descent.

## Challenging, interesting, or exciting aspects of today's assignment
What I found the most interesting was the process of comparing all the different optimizers and visualizing them. I also enjoyed using Keras implementation of the AdaGrad optimizer and comparing it to the rest to see it's performance.

## Additional resources used 
chatGPT for grammatical errors, code errors and some definitions. 

Blog by Saturn Cloud titled "PyTorch Understanding the Connection Between lossbackward and optimizerstep" (link: https://saturncloud.io/blog/pytorch-understanding-the-connection-between-lossbackward-and-optimizerstep/#:~:text=The%20optimizer%20is%20responsible%20for,biases%20to%20minimize%20this%20difference) 

StackExchange question "Is Gradient Descent central to every optimizer?" 
(link: https://datascience.stackexchange.com/questions/47142/is-gradient-descent-central-to-every-optimizer)

StackExchange question "Batch gradient descent versus stochastic gradient descent" (link: https://stats.stackexchange.com/questions/49528/batch-gradient-descent-versus-stochastic-gradient-descent)

Article by user nishkarsh146 titled "Difference between Batch Gradient Descent and Stochastic Gradient Descent" (link: https://www.geeksforgeeks.org/difference-between-batch-gradient-descent-and-stochastic-gradient-descent/#article-meta-div)

Article by Afaf Athar titled "Activation Functions, Optimization Techniques, and Loss Functions" (link: https://medium.com/analytics-vidhya/activation-functions-optimization-techniques-and-loss-functions-75a0eea0bc31) 

Article by Jason Brownlee titled "How to Choose an Activation Function for Deep Learning" (link: https://machinelearningmastery.com/choose-an-activation-function-for-deep-learning/) 
