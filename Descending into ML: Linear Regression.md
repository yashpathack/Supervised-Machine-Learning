Case: Crickets chirp more frequently on hotter days than on cooler days. For decades, professional and amateur entomologists (Those who study insects) have cataloged data on chirps-per-minute and temperature
Let's observe a graph based on this chirping and temperature in celsius.
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/8.png)
These tiny red dots denote the chirping instant wrt ot temperature and time. So we plotted the data

We can see the no. of chirps rising as the temperature goes up. This is a linear relation. Hence let's draw a straight line in the most acceptable zone. 
![alt text](https://github.com/yashpathack/Supervised-Machine-Learning/blob/master/Resources/9.png)

This can be formulate this realtionship in the form of: y = mx + b
y = temp in C
m = slope
x = times chirp in minute - value of input feature
b = the y intercept

But for ML we're gonna use some slightly different notions, hence reframing it as:
y' = b + w<sub>1</sub>x<sub>1</sub>






