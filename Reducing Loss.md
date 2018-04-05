# Training a model using an iterative approach
How to chose a set of model parameters?<br>
We need a direction to go into parameter space. To minimize the loss.<br>
One way is to compute the gradient i.e the derivative of the loss function with the model parameter. <br>

> For simple loss fucntions like the square loss function (L2) it's easy to compute the derivative. This gives us an efficient way to update model parameters. An iterative approach.<br>
#### How do we reduce loss?<br>
> Derivative of (y - y')2 with respect to the weights and biases tells us how loss changes for a given example. Simple to compute and convex<br>
> So we repeatedly take small steps in the direction that minimizes loss<br>
> We call these Gradient Steps (But they're really negative Gradient Steps)<br>
> This optimization strategy is called Gradient Descent<br>
