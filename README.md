# A-Mathematical-Theory-of-Learning
---
##Dec 27 2017
* This repository is created for the research upon a mathematical understanding of learning. 

* ---

  ### The motivation of the work: underfitting and overfitting ML models

* The work here is motivated by the problem of [underfitting and overfitting](https://en.wikipedia.org/wiki/Overfitting) in Machine Learning industry.

  Using binary classification as an example, currently we say a ML model is underfitting if on a test set, it is not recognizing enough positive examples; we say a ML model is overfitting if on a test set, it is overkilling too many negative examples. 

* Underfitting is describing the phenomena that a ML model fails to grasp all the information provided during training, such that it is not able to complete the structure of the test set with satisfactory precision. 

* Overfitting on the other hand, is describing the phenomena that a ML model is over biased on some features in the training set, such that it constructs a test set much too resembles the training set.

* Borrowing the description of Burnham & Anderson[^1], an overfitting model remembers rather than generalizing the trend in the training set to the test set, while an underfitting model fails to capture some key structure in the training set.

  ---

  ​

* Naturally for each ML model, there should be a critical point where the model is neither overfitting nor underfitting, that the model has learned just the right amount of knowledge from the training set, and NOT biased towards some particular features.
---
* ### The big question of the research

* Then comes the big question: what do we mean by "learned just the right amount"? 

* Seems like "Learning all necessary structures" and "Not introducing extra noise and bias". But this is far from mathematical. 

* **It is interesting to think about if there is a precise measure of the quantity that a model learns.**

* The result can be generalized to the learning capacity of a human being, or other intelligible entities that have the ability to learn.
---
[^1]: Burnham,K. P.; Anderson, D. R. (2002), Model Selection and Multimodel Inference (2nd ed.), Springer-Verlag. 
