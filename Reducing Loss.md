# Training a model using an Iterative Approach
How to chose a set of model parameters?<br>
We need a direction to go into parameter space. To minimize the loss.<br>
One way is to compute the gradient i.e the derivative of the loss function with the model parameter. <br>

> For simple loss fucntions like the square loss function (L2) it's easy to compute the derivative. This gives us an efficient way to update model parameters. An iterative approach.<br>
#### How do we reduce loss?<br>
> Derivative of (y - y')2 with respect to the weights and biases tells us how loss changes for a given example. Simple to compute and convex<br>
> So we repeatedly take small steps in the direction that minimizes loss<br>
> We call these Gradient Steps (But they're really negative Gradient Steps)<br>
> This optimization strategy is called Gradient Descent<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/15.png)
>> Data comes in, we compute the gradient of the loss function on that data.
	The negative gradient tells us in which direction to update model parameters
	in order to reduce loss. We take a step in that direction,
	get a new version of the model, and now we can recompute the gradient and repeat.
	
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/Reducing%20Loss/image.png)
> 	
Pretend in one dimension, this is our loss function.
It maps our single model parameter theta to the loss.
If we start off at a random value or initialization for theta
then we achieve a corresponding loss.
We can then compute the negative gradient which tells us
in which direction we should go in order to minimize the loss.
If we take a gradient step in that direction we get a new loss.
We can keep taking gradient steps in that direction until we've reached a point
in which we have passed the local minimum, in which the
negative gradient will tell us to go back in the direction t
