## Training
> Training means learning useful and good values for all weights and biases from labeled examples.
In supervised learning, the algorithm builds a model by examining many examples and attempting to find model that minimizes  loss.
This process is called <b>empirical risk minimization.</b>

## Loss
> Loss is the penalty for bad prediction. Loss is a number indicating how bad the model's prediction was on a certain example.
If the loss is zero then the prediction is perfect. Or else the loss is greater. 
So what we want to do is find the set of weights and biases that have a low loss, on average on all of the examples considereed.<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/10.png)<br>
> The red arrow represents loss.
> The blue line represents predictions. <br>
Higher loss in left model. Low loss in the right model

The red arrows in the left model are much longer than their counterparts in the right plot. Clearly, the blue line in the right plot is a much better predictive model than the blue line in the left plot.

## Squared Loss: A popular loss function
> The squared loss function is calls L<sub>2</sub> function.
= the square of the difference between the label and the prediction
  = (observation - prediction(x))2
  = (y - y')2 <br>
  
 ## The Mean Square error (MSE) 
  ![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/11.png)<br>
<br>
  
Mean square error (MSE) is the average squared loss per example. To calculate MSE, sum up all the squared losses for individual examples and then divide by the number of examples.

where:

 (x,y) is an example in which
 x is the set of features (for example, chirps/minute, age, gender) that the model uses to make predictions.
 y is the example's label (for example, temperature).
 __prediction(x)__ is a function of the weights and bias in combination with the set of features x.
 __D__ is a data set containing many labeled examples, which are (x,y) pairs.
 __N__ is the number of examples in D
 MSE is commonly-used in machine learning, it is neither the only practical loss function nor the best loss function for all circumstances.
 



