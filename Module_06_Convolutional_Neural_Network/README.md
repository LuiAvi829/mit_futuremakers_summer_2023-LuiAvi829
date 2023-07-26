# Convolution Neural Network

## Topics covered in today's module
* Convolution neural network components
* Visualizing kernels
* Visualizing feature maps
* Pooling
* Dropout
* Batch norm

## Main takeaways from doing today's assignment
What is a filter used for? Filters are used to extract different features in a same layer. When the same filter is used in each row the reason behind it is to look for the same pattern but in different spacial position in the input data. 

I learned the code to successfully visualize feature maps with FASHION MNIST data set. 

Dropout layer help with creating ensemble networks, which makes predictions based on a number of smaller networks instead of one big newtowrk. Dropout layers should be used when trying to reduce overfitting, this is when the model gets to complex. Also thay can be used when working with ensemble learning. 

Batch normalizing layers work by looking at each batch that comes in, it then normalizes it with it's own mean and standard deviation, it then puts the data in a new scale. It can help with accelerating training that is too slow, also can help with vanishing or exploding gradients.

## Challenging, interesting, or exciting aspects of today's assignment
What I found the most challenging, interesting and exciting part of this assignment was the visualization of feature maps. While initially challenging, I found the process immensely rewarding as I gained a comprehensive understanding and successfully implemented the visualization. 

## Additional resources used 
I used chatGPT to correct code erros, grammatical errors and for definitions of concepts.

I used an article from kaggle by Ryan Holbrook called Dropout and Batch Normalization (link: https://www.kaggle.com/code/ryanholbrook/dropout-and-batch-normalization) 


