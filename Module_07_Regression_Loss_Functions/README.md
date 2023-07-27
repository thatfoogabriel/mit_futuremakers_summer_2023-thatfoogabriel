# Regression Loss Functions

## Topics covered in today's module
* Mean Squared Error
* Mean Absolute Error
* Mean Squared Logarithm Error

## Main takeaways from doing today's assignment
&minus; Mean Squared Loss: $$MSE = \frac{\sum_{i=1}^{n}(y_i-\hat{y}_i)^2}{n}$$
- &bull; Harshly penalizes large errors
- &bull; Sensitive to outliers since differences are squared
- &bull; Continuous and differentiable loss, useful for gradient optimization of parameters
- &bull; Best with data with no outliers and for minimizing large errors
<br></br>

&minus; Mean Absolute Loss: $$MAE = \frac{\sum_{n=1}^{n}|y_i - \hat{y}_i|}{n}$$ 
- &bull; Penalizes all errors equally
- &bull; Less sensitive to outliers since it calculates absolute differences
- &bull; Continuous, but not differentiable at 0, not a problem during optimization
- &bull; Best when data has outliers and predicting central tendency
<br></br>

&minus; Mean Squared Logarithmic Loss: $$MSLE = \frac{\sum_{i=1}^{n}(\log(y_i+1) - \log(\hat{y}_i+1))^2}{n}$$
- &bull; Precisely calculates small values close to zero
- &bull; Less sensitive to outliers since values are scaled down using log
- &bull; Continuous and differentiable loss, useful for gradient optimization of parameters
- &bull; Best for large data sets, or data with small values

## Challenging, interesting, or exciting aspects of today's assignment
&minus; When using MSLE, 1 is added to the output values during calculation
- This is done to avoid taking the log of very small numbers or 0. Since the exact value of the loss isn't as important to us as the overall shape of the line, adding 1 isn't harmful.

## Additional resources used 
[Mean Squared Loss](https://www.geeksforgeeks.org/ml-common-loss-functions/) \
[Mean Absolute Loss](https://www.geeksforgeeks.org/how-to-measure-the-mean-absolute-error-mae-in-pytorch/) \
[Mean Squared Logarithmic Loss vs. Mean Squared Loss](https://builtin.com/data-science/msle-vs-mse) \
[TensorFlow Loss Functions](https://www.tensorflow.org/api_docs/python/tf/keras/losses) \
[TensorFlow Metrics](https://www.tensorflow.org/api_docs/python/tf/keras/metrics)
