# Deep Learning and TensorFlow

## Topics covered in today's module
* Linear models in machine learning
* Introduction to TensorFlow
* Dataloaders
* Building a simple Neural Network

## Main takeaways from doing today's assignment
&minus; Neural Networks usually scale input and output values down bewteen 0 and 1:
- All values will be wieghed equally (ex: splitting image into pixels with highly varying values)
- Different units of measurements will be accounted for
- Output values will be easier to pass to the activation function

&minus; Adding more layers = account for more relationships between features
&minus; Adding more nodes = more precise feature detection, fewer generalizations
The more layers and nodes, the lower the loss and the higher the accuracy per epoch

## Challenging, interesting, or exciting aspects of today's assignment
<div align=center><img src="https://miro.medium.com/v2/resize:fit:1400/1*WfERQXN_BtLi1eAh36_mvw.png" width=40% height=40%></div> 

&minus; Sigmoid Activation Function: 
- Better for binary classification problems, where there are only two classes
- Ex: Cat vs. Dog Classifier

&minus; Softmax Activation Function: 
- Better for multiclass classification problems, where there are many classes
- Ex: Dog Breed Classifier


## Additional resources used 
[Scikit Learn Linear Regression Model](https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LinearRegression.html) \
[Scaling Data Values](https://machinelearningmastery.com/how-to-improve-neural-network-stability-and-modeling-performance-with-data-scaling/#:~:text=Scaling%20Input%20Variables,a%20standard%20deviation%20of%20one.) \
[Scaling Data Values](https://stats.stackexchange.com/questions/603855/why-data-scaling-in-range-0-1-is-important) \
[Sigmoid vs. Softmax Activation Functions](https://towardsdatascience.com/sigmoid-and-softmax-functions-in-5-minutes-f516c80ea1f9#:~:text=But%20if%20both%20functions%20map,extension%20of%20the%20Sigmoid%20function.) \
[ReLu Activation Function](https://machinelearningmastery.com/rectified-linear-activation-function-for-deep-learning-neural-networks/) \
[Overfitting and Underfitting](https://docs.aws.amazon.com/machine-learning/latest/dg/model-fit-underfitting-vs-overfitting.html)
