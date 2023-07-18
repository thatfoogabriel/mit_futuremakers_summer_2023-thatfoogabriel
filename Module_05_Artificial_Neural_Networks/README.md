# Artificial Neural Networks

## Topics covered in today's module
* Introduction to Neural Networks
* Hyperparameters
* Forward Pass
* Backpropagation
* Computing accuracy

## Main takeaways from doing today's assignment
<div align=center><img src="https://miro.medium.com/v2/resize:fit:1400/1*q1M7LGiDTirwU-4LcFq7_Q.png" width=60% height=60%></div> 

&minus; Forward Pass:
- &bull; Input data passed through each layer, being modified by parameters (weights and biases)
- &bull; Each layer's outputs serve as next layer's inputs
- &bull; Used to make predictions at the output layer
<br></br>

&minus; Backward Pass (Backpropogation):
- &bull; Calculate the gradient of loss at each layer using the chain rule of calculus
- &bull; Starts from the output layer to the input layer
- &bull; Determines how much each parameter contributed to the total loss
- &bull; Used to optimize parameters after each iteration
<br></br>

&minus; One iteration = One cycle of Forward Pass then Backward Pass

## Challenging, interesting, or exciting aspects of today's assignment
&minus; Fun to see a neural network coded manually with all its parts!
- &bull; <ins>Input, Output, and Hidden Layers:</ins> with initial parameters
- &bull; <ins>Activation Function:</ins> to introduce non-linearity
- &bull; <ins>Forward Pass:</ins> to calculate output from inputs
- &bull; <ins>Backward Pass:</ins> to improve accuracy
- &bull; <ins>Stochastic Gradient Descent (SGD):</ins> to update parameters
- &bull; <ins>Accuracy Function:</ins> to determine success of training
- &bull; <ins>Training Loop:</ins> to iteratively run training data

## Additional resources used 
[ReLu Activation Function](https://en.wikipedia.org/wiki/Rectifier_(neural_networks)) \
[Xavier Initialization](https://pouannes.github.io/blog/initialization/#xavier-and-kaiming-initialization) \
[Xavier Initialization](https://365datascience.com/tutorials/machine-learning-tutorials/what-is-xavier-initialization/) \
[NumPy RandN](https://numpy.org/doc/stable/reference/random/generated/numpy.random.randn.html) \
[Foward and Backward Pass](https://towardsdatascience.com/neural-networks-forward-pass-and-backpropagation-be3b75a1cfcc) 
