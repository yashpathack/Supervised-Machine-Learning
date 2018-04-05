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
The squared loss function is calls L<sub>2</sub> function.
= the square of the difference between the label and the prediction
  = (observation - prediction(x))2
  = (y - y')2 <br>
  ![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/11.png)<br>
<br>
  

 



