Model is something that learns from data.
Let's take an example in here. Here we have a data with inputs along x axis and the outputs denoted as the blueish dots.<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/1.png)<br>

Now let's draw a line through the most probable regions in the graph. A straight line ofcourse.<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/2.png)<br>

Now, this is a stamdard slope equation y = mx + c. In this case we have w i.e weights. And b is the distance from origin to the outgrowth of the blue line<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/3.png)<br>

Here we can obviously see that there is loss. The red vertical lines from the main blue line is loss. it maybe positive or negative. But magnitude of loss is either zero or more.<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/4.png)<br>

Now how to calculate loss?
Let's start with the basic L<sub>2</sub> loss.
It is given by: 
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/5.png)<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/7.png)<br>

= Square of the difference between prediction and label
= (observation - prediction)2
= (y - y')2

![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/6.png)<br>
Little did i know, this thing is called linear regression.
