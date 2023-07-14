# Deep Learning and TensorFlow

## Topics covered in today's module
* Linear models in machine learning
* Introduction to TensorFlow
* Dataloaders
* Building a simple Neural Network

## Main takeaways from doing today's assignment
Linear Regression:

Linear regression models establish a connection between features and targets to predict continuous values based on a linear relationship.

The .score() method calculates the coefficient of determination or R-squared value to evaluate the model's fit using the input data and target values.

The .coef_ attribute returns the coefficients, which can be a 1D or 2D array depending on the number of features passed in the model. Positive coefficients indicate a positive relationship with the target, while negative coefficients indicate an inverse relationship.

The .intercept_ attribute provides the intercept or bias term in the linear regression model, representing the estimated target value when independent variables are set to zero.

Neural Networks:

Care must be taken when adding layers and nodes to avoid overfitting, where the model becomes too complex and memorizes the training data instead of learning patterns. Regularization techniques, increased training duration, or obtaining more data can help mitigate overfitting.

Sigmoid and Softmax functions are used in neural networks. Sigmoid is suitable for binary classification, producing probabilities between 0 and 1 for independent binary classifications. Softmax is used for multi-class classification and requires the number of nodes to match the number of classes.

Scaling Data:

Scaling data to a smaller range, like 0-1, is important because it improves neural network performance and stability.
Scaling helps prevent issues like vanishing or exploding gradients, improves optimization efficiency, and ensures compatibility with activation functions.

Scaling data to a common range facilitates efficient learning, prevents shifts to larger values during optimization, and helps the network focus on relative relationships and patterns rather than absolute values.

## Challenging, interesting, or exciting aspects of today's assignment
What I would say was the most challenging, interesting and exciting aspect of this assignment was experimenting with layers and nodes. I really enjoyed this because I was curious to see what would happen if I decrease or increase the numbers and I will be lookin forward to learning and working with them more.

## Additional resources used 
chatGPT: I used it to ask questions about different concepts, like the difference between sigmoid and SoftMax, also used it to correct grammatical errors in my writing and to ask question about the meaning of different code lines.

scikit learn: i used it read about score(), coef_ and intercept_ (link: https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html#sklearn.linear_model.LinearRegression) 

Article titled Activation Functions in Neural Networks by Sagar Sharma: I used it to read more about sigmoid (link: https://towardsdatascience.com/activation-functions-neural-networks-1cbd9f8d91d6) 

Article titled The Differences between Sigmoid and Softmax Activation Functions by Nikola Basta: I used it to read about the main differences between sigmoid and SoftMax. (link: https://medium.com/arteos-ai/the-differences-between-sigmoid-and-softmax-activation-function-12adee8cf322#:~:text=Softmax%20is%20used%20for%20multi,in%20the%20Logistic%20Regression%20model.)


