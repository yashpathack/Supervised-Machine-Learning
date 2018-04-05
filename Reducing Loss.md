# Training a model using an iterative approach
How to chose a set of model parameters?
We need a direction to go into parameter space. To minimize the loss.
One way is to compute the gradient i.e the derivative of the loss function with the model parameter. 

> For simple loss fucntions like the square loss function (L2) it's easy to compute the derivative. This gives us an efficient way to update model parameters. An iterative approach.
#### How do we reduce loss?
> Derivative of (y - y')2 with respect to the weights and biases tells us how loss changes for a given example. Simple to compute and convex
> So we repeatedly take small steps in the direction that minimizes loss
> We call these Gradient Steps (But they're really negative Gradient Steps)
> This optimization strategy is called Gradient Descent
