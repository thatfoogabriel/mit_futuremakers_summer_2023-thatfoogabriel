# Machine Learning

## Topics covered in today's module

* Introduction to Machine Learning
* Machine learning with Scikit-learn
* Decision Trees
* Linear Regression
* Random Forests

## Main takeaways from doing today's assignment
<div align=center><img src="https://1394217531-files.gitbook.io/~/files/v0/b/gitbook-legacy-files/o/assets%2F-LvBP1svpACTB1R1x_U4%2F-LwQbcbsD6nnVTHSgxV1%2F-LwQcH6NWMz6kjAEqpge%2Fimage.png?alt=media&token=2ccddf94-0321-472e-a2dd-49e7ab63914d" width=50% height=50%></div>

- <ins>Supervised Learning:</ins> Match labeled input data to labeled outputs (Classification, Regression)
- <ins>Unsupervised Learning:</ins> Draw conclusions from features of input data (Clustering, Dimensionality Reduction)
- <ins>Reinforcement Learning:</ins> Model performs actions in an environment, rewarded by evaluative feedback function (Walking Robot, Chess AI)
<br></br>

&minus; Decision Tree vs. Random Forest:
- Similarities:
- - Supervised Learning Style: need labeled data
- - Tree Structure: branching decisions and classification paths
- - Feature Importance: help identify which features can make or break a classification
- Differences:
- - Random Forests are made up of many Decision Trees, allowing for more features to be accounted for
- - Forests account for bias and outliers, which lead to more accurate results
- - Decision Trees are faster to train and easier to understand visually

## Challenging, interesting, or exciting aspects of today's assignment
&minus; Gini Impurity: Probability of misclassifying a given data point
- Lower gini = lower chance of misclassification
- Calculated as 1 minus the sum of all the squared probablities of each element
- Decision Trees find paths with minimal changes in gini
<div align=center><img src="https://i.stack.imgur.com/E7Fak.png" width=20% height=20%></div>
<div align=center><img src="https://upload.wikimedia.org/wikipedia/commons/5/59/Economics_Gini_coefficient2.svg" width=30% height=30%></div>

## Additional resources used 
[Machine Learning Cheat Flow Map](https://maps.joindeltaacademy.com/) \
[Random Forest Initialization](https://scikit-learn.org/stable/modules/ensemble.html#forests-of-randomized-trees) \
[Lars-Lasso Model](https://scikit-learn.org/stable/modules/linear_model.html#lars-lasso) \
[Gini Impurity](https://blog.quantinsti.com/gini-index/) \
[Gini Impurity](https://www.learndatasci.com/glossary/gini-impurity/) \
[How Decision Trees use Gini Index](https://towardsdatascience.com/decision-trees-explained-entropy-information-gain-gini-index-ccp-pruning-4d78070db36c)
