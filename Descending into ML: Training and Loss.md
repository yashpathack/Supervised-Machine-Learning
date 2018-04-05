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
  Products   Crash Course   Course
Descending into ML: Training and Loss
Estimated Time: 6 minutes
Training a model simply means learning (determining) good values for all the weights and the bias from labeled examples. In supervised learning, a machine learning algorithm builds a model by examining many examples and attempting to find a model that minimizes loss; this process is called empirical risk minimization.

Loss is the penalty for a bad prediction. That is, loss is a number indicating how bad the model's prediction was on a single example. If the model's prediction is perfect, the loss is zero; otherwise, the loss is greater. The goal of training a model is to find a set of weights and biases that have low loss, on average, across all examples. For example, Figure 3 shows a high loss model on the left and a low loss model on the right. Note the following about the figure:

The red arrow represents loss.
The blue line represents predictions.
Two Cartesian plots, each showing a line and some data points. In the first plot, the line is a terrible fit for the data, so the loss is high. In the second plot, the line is a a better fit for the data, so the loss is low.

Figure 3. High loss in the left model; low loss in the right model.

 

Notice that the red arrows in the left plot are much longer than their counterparts in the right plot. Clearly, the blue line in the right plot is a much better predictive model than the blue line in the left plot.

You might be wondering whether you could create a mathematical function—a loss function—that would aggregate the individual losses in a meaningful fashion.

Squared loss: a popular loss function
The linear regression models we'll examine here use a loss function called squared loss (also known as L2 loss). The squared loss for a single example is as follows:

  = the square of the difference between the label and the prediction
  = (observation - prediction(x))2
  = (y - y')2
Mean square error (MSE) is the average squared loss per example. To calculate MSE, sum up all the squared losses for individual examples and then divide by the number of examples:

where:

 (x,y) is an example in which
 x is the set of features (for example, chirps/minute, age, gender) that the model uses to make predictions.
 y is the example's label (for example, temperature).
 __prediction(x)__ is a function of the weights and bias in combination with the set of features x.
 __D__ is a data set containing many labeled examples, which are (x,y) pairs.
 __N__ is the number of examples in D
 MSE is commonly-used in machine learning, it is neither the only practical loss function nor the best loss function for all circumstances.
 



