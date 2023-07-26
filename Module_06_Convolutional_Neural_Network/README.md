# Convolution Neural Network

## Topics covered in today's module
* Convolution neural network components
* Visualizing kernels
* Visualizing feature maps
* Pooling
* Dropout
* Batch norm

## Main takeaways from doing today's assignment
&minus; Dropout Layers:
- &bull; Node outputs are randomly ignored
- &bull; Forces model to look for different feature hints
- &bull; Useful when model becomes too reliant on one or more features to make predictions
<br></br>

&minus; Batch Layers:
- &bull; Regularization of input weights to a smaller range of values
- &bull; Done by subtracting the mean and dividing by the standard deviation of the mini-batch values
<div align=center><img src="https://miro.medium.com/v2/resize:fit:1160/1*WHO0ASlCE8grh3f_c6hFOA.png" width=40% height=40%></div> 

- &bull; Useful when model varies too much based on initial parameter values
- &bull; Also useful with varied data sets since it reduces sensitivity to input distributions
<br></br>

&minus; Both of these regularization techniques fight overfitting and underfitting and streamline training by speeding up convergence
## Challenging, interesting, or exciting aspects of today's assignment
&minus; The main limiting factor of an AI model being successful is having enough training data
- **How do we train a model when there is little useful data?**
- - &bull; Dropout Layers introduce a form of noise by removing random node outputs
<br></br>
- ***Introducing randomness is one way to circumvent small datasets. Introducing noise by randomly modifying weight values or adding dropout layers could help imitate data inputs that could exist, but aren't present in the training data set.***

## Additional resources used 
[Convolutional Neural Networks](https://towardsdatascience.com/convolutional-neural-networks-explained-9cc5188c4939) \
[Convolutional Neural Networks](https://stackoverflow.com/questions/52272592/how-many-neurons-does-the-cnn-input-layer-have) \
[Dropout Layer Regularization](https://www.analyticsvidhya.com/blog/2022/08/dropout-regularization-in-deep-learning/) \
[Dropout Layer Regularization](https://machinelearningmastery.com/dropout-for-regularizing-deep-neural-networks/) \
[Batch Layer Normalization](https://machinelearningmastery.com/batch-normalization-for-training-of-deep-neural-networks/) \
[Batch Layer Normalization](https://www.pinecone.io/learn/batch-layer-normalization/) \
[TensorFlow Compile Function](https://www.tensorflow.org/api_docs/python/tf/keras/Model#compile) \
[TensorFlow Optimizers](https://www.tensorflow.org/api_docs/python/tf/keras/optimizers) \
[TensorFlow Loss Functions](https://www.tensorflow.org/api_docs/python/tf/keras/losses) 
