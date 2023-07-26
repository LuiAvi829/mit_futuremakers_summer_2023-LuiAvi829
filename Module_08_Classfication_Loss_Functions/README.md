# Classification Loss Functions

## Topics covered in today's module
* Kullback Leibler Divergence Loss
* Binary Cross-Entropy
* Categorical Cross-Entropy
* Sparse Categorical Cross-Entropy

## Main takeaways from doing today's assignment
Kullback-Leibler Divergence (KDL): This divergence is a measure of how one probability distribution differs from another. In the context of machine learning, it is often used as a loss function to measure the difference between the predicted probability distribution and the actual target distribution. 

Binary Cross-entropy (BCE): BCE is used in binary classification where there are only two classes and the data can fit into one of the two. Also, BCE uses sigmoid activation function(outputs the probabilities between 0 and 1). When calculating the loss BCE calculated for each binary class independently, then adds them or calculates the average.

Categorical Cross-Entropy (CCE): CCE is a multi-class classification where each data belongs to one class out of multiple classes, for this reason CCE works with multiple classes at the same time. CCE uses SoftMax activation function(outputs a probability distribution over all classes, all the probabilities add to 1). And for the calculation of the loss it considers he complete predicted probability distribution and the corresponding one-hot true label. It encourages the model to correctly assign high probabilities to the true class and low probabilities to other classes.

Sparse Categorical Cross-Entropy (Sparse CCE): Sparse Categorical Cross-Entropy is similar to Categorical Cross-Entropy but is specifically used when the target labels are represented as integers instead of one-hot encoded vectors. It is more memory-efficient for large datasets with a significant number of classes, as it avoids the need to one-hot encode the target labels. Sparse CCE calculates the loss using the predicted probability of the true class index without the need for one-hot encoding. 

## Challenging, interesting, or exciting aspects of today's assignment
I found this assignment very interesting, learning about Kullback Leibler Divergence Loss, Binary Cross-Entropy, Categorical Cross-Entropy, Sparse Categorical Cross-Entropy. Understanding their characteristics and applications has thought me valuable insights for enhancing machine learning practices.

## Additional resources used 
I used chatGPT for program errors, grammatical errors and for some definitions of concepts.

Article by Jason Brownlee titled "How to Calculate the KL Divergence for Machine Learning" (link: https://machinelearningmastery.com/divergence-between-probability-distributions/#:~:text=The%20Kullback%2DLeibler%20Divergence%20score,KL(P%20%7C%7C%20Q)) 

Article by Amber Roberts titles "Binary Cross Entropy: Where To Use Log Loss In Model Monitoring" (link: https://arize.com/blog-course/binary-cross-entropy-log-loss/#:~:text=What%20Is%20Binary%20Cross%20Entropy,equate%20to%20high%20accuracy%20values.) 

Article by Deval Shah titled "Cross Entropy Loss: Intro, Applications, Code" 
(link: https://www.v7labs.com/blog/cross-entropy-loss-guide#:~:text=Categorical%20Cross%20Entropy%20is%20also,N%20classes%20for%20each%20image.)

I used an article from tensorflow titled "tf.keras.losses.SparseCategoricalCrossentropy" to read about Sparce CCE 
(link: https://www.tensorflow.org/api_docs/python/tf/keras/losses/SparseCategoricalCrossentropy
