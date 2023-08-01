# Regularization

## Topics covered in today's module
* L1/L2 Regularization
* Dropout
* Overfitting
* Underfitting

## Main takeaways from doing today's assignment
Regularization: is a technique used to avoid overfitting, it does this by adding penalties to the model during the training time. The result is a more generalized and robust model the can preform better with unseen data.

L1 Regularization: inserts a penalty term to the loss function based on the absolute values of the model's weights. It encourages the model to have fewer relevant features by driving some weights to exactly zero, promoting a more interpretable and sparse model.

L2 Regularization: inserts a penalty term to the loss function based on the squared values of the model's weights. By discouraging overly large weight values, this regularization leads to smoother and more stable models, resulting in better generalization capabilities.

Dropout: Dropout is a regularization method commonly used in neural networks. During training, randomly selected neurons are "dropped out" or removed with a specified probability. This helps prevent co-adaptation of neurons and encourages the network to be more robust and less reliant on specific neurons, reducing overfitting.

## Challenging, interesting, or exciting aspects of today's assignment
What I found the most interesting was the use regularization and their importance in nerual networks, by preventing overfitting, enhancing model performance, and ensuring generalizability to unseen data.

## Additional resources used 
chatGPT for code errors, grammatical errors and some definitions

Article by Raimi Karim titled "https://towardsdatascience.com/intuitions-on-l1-and-l2-regularisation-235f2db4c261" (link: https://towardsdatascience.com/intuitions-on-l1-and-l2-regularisation-235f2db4c261)

Article by Jeremy Zhang titled "Regularization & Dropout in Deep Learning" (link: https://towardsdatascience.com/regularization-dropout-in-deep-learning-5198c2bf6107) 
