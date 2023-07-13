# Machine Learning

## Topics covered in today's module

* Introduction to Machine Learning
* Machine learning with Scikit-learn
* Decision Trees
* Linear Regression
* Random Forests

## Main takeaways from doing today's assignment

The main takeaways form todays assignment were:
  Supervised learning: this is when a machine learns by giving it a sample data, and this data contains an example of athe input and output that it should learn. There are two types of supervised learning aproaches: 
      Classification: the goal of this aproach is to classify the data in different groups depnding on their features, like what was worked on with the iris data set.
      Regression: Like to classfication aproach it uses inputs and their outputs, but unlike classification the output is not discrete it is a sliding scale of possibilities, nut only 0 and 1. 
      
  Unsupervised learning: this is when the machine learns the desired outputs by itself, you give it example input samples but not the output smaples. There are two types of unsupervised learning aproaches:
      Cluster: in this method only the input data is given a there is not explicit output data given. With the input data the machin can learn what is needed.
      Dimensionality Reduction: this method compresses the data given into a smaller and different group, this way it can keep the most important of the original features while minimising data loss.
      
  Semi-supervised learning: this is a combination of supervised and unsupervised learning. It uses a small group of unlabeld data to gain a sense to the structure of the data and it also uses a small group of labeled data to learn how to group the complete data.

  Reinforcement learning: this method is like the unsupervised learning, becuase the outputs are usually not given. It is based on an "agent", which is a computer or a robot, it's task is to interact with the "environment", which is everything that is not the agent. The agent interacts with the enviorment and as a result it gains a result in the form a "reward", which is the enviorments feedback to the agent.

Another thing that I learn with this assigment where Decision Trees and Random Forests
  Gini: The Gini index is a measure of impurity or uncertainty used in decision trees. It quantifies how accurately a decision tree makes decisions from the root node to all the leaf nodes. A lower Gini index indicates a more optimal split and a higher level of purity in the resulting subsets. A high Gini index suggests that the decision tree's splitting criterion may not be capturing the underlying patterns or structure of the data as effectively, potentially leading to less accurate predictions.
  
  Decision Tree: It's a supervised leatning method that is commonly used as a classification model and can handle categorical target variables effectively. Decision Trees build a hierarchical structure of if-else rules based on feature values to make decisions. Decision Trees can capture nonlinear relationships and identify decision boundaries between different classes. 
  
  Random Forest: Random Forests are mush like the Decision Trees, it is also a supervised learning method, but the main difference is that a forest is composed of multiple Decision Trees , not just one. They offer improved accuracy but require more training time. 
  
Finally, Linear Regression: it is primarily designed for predicting continuous values based on a linear relationship. It assumes a linear relationship between the input features and the target variable, making it more suitable for regression tasks. Unlike the Decision Tree and Random Forest, this a regression not a classification method. 

## Challenging, interesting, or exciting aspects of today's assignment

What I found the most challenging, interesting and exciting part of this assignment were the Decision Trees and Random Forest, becuase as someone who had not previously delved into these algorithms, it presented an intriguing opportunity to learn something new and apply it in a practical context.

## Additional resources used 
chatGPT: I used it to ask questions of different definitions, like what is a Gini in the Decision Trees and if I had an error in my code so I could fix it. 
I used an article titled A Gentle Introduction to Machine Learning Concepts by Robbie Allen to learn a read about the different types of learning methods. (link: https://medium.com/machine-learning-in-practice/a-gentle-introduction-to-machine-learning-concepts-cfe710910eb)
Scikit learn to read about Ridge regression and classification. (link: https://scikit-learn.org/stable/modules/linear_model.html#ridge-regression-and-classification)
upGrad blog to learn about the differneces and similarities between Decision Trees and Random Forest. (link: https://www.upgrad.com/blog/random-forest-vs-decision-tree/)
ML Corner blog to learn about Linear Regressions and Decision Trees. (link: https://mlcorner.com/linear-regression-vs-decision-trees/)

