# -heart_diseases_2_hidden-


Questions:
1. What are the dimensions of the matrices you will use to represent your model (inputs, parameters, and
outputs)? How will you integrate the concept of mini-batch training?
Mini-batch gradient descent is a variation of the gradient descent algorithm that splits the training dataset into,
small batches that are used to calculate model error and update model coefficients.


2. How to check whether or not you should keep training your model?

Early stopping

The idea behind this approach lies in the comparison between the training set and the test set or, for more reliable results,
between the training set and the validation set.

By analyzing the error or loss graph in both the training and validation splits as the epochs pass, we will see that at first both decrease. 
However, the validation error will start to flatten out or increase at a certain time while the training error will continue to decrease.














Reference sources:
https://www.youtube.com/watch?v=yXcQ4B-YSjQ
https://www.kaggle.com/code/rishabhdhiman/neural-network-from-scratch-using-numpy
https://machinelearningmastery.com/gentle-introduction-mini-batch-gradient-descent-configure-batch-size/
https://towardsdatascience.com/the-million-dollar-question-when-to-stop-training-deep-learning-models-fa9b488ac04d
