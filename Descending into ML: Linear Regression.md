# Linear Regression
Case: Crickets chirp more frequently on hotter days than on cooler days. For decades, professional and amateur entomologists (Those who study insects) have cataloged data on chirps-per-minute and temperature
Let's observe a graph based on this chirping and temperature in celsius.<br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/8.png)
<br>These tiny red dots denote the chirping instant wrt ot temperature and time. So we plotted the data

We can see the no. of chirps rising as the temperature goes up. This is a linear relation. Hence let's draw a straight line in the most acceptable zone. <br>
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/9.png)
<br>
This can be formulate this realtionship in the form of: y = mx + b
y = temp in C
m = slope
x = times chirp in minute - value of input feature
b = the y intercept

But for ML we're gonna use some slightly different notions, hence reframing it as:
y' = b + w<sub>1</sub>x<sub>1</sub>
y = predicted label (the desired output)
b is called the bias(the y intercept). Sometimes it may be referred to as w<sub>0</sub>
w<sub>1</sub> is the weight of the featur 1. Weight is same as slope. 
x<sub>1</sub> is a feature (a known input)

To infer(predict) the temperature in y' for new chirps per min value x1, just plug the x1 value into the model
The subscripts (for example, w1 and x1) foreshadow more sophisticated models that rely on multiple features. For example, a model that relies on three features would use the following equation: 
y1 = b + w1x1 + w2x2 + w3x3





