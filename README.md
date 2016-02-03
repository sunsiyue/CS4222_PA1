# CS4222_PA1

This is a CS4222 project

Sun Siyue A0101491U
Guo Xiang A0112659A
Ji Yahui  A0101973J

Task1:
When outdoors, the readings normally is higher than 3000. 
When indoors, the readings is generally not more than 1000.

Task3:
Base on the theory we used to detect indoor/outdoor, we only depend on the readings of the 
light sensor. When the readings is above a specific number(1000),we say the user is outdoor. Vise versa. 
But there is some special conditions which will affact the readings of the light sensor.
For example, when user is outdoor, if the light sensor is in shadow or user put the phone in pocket
or it is after sunset, the readings of the light sensor may below 1000. Based on our defination, we define 
the user is ourdoor. 
Another example is that when user is indoor, if the light sensor is very close to the light source, the 
readings of the light sensor will above 1000. Which based on our defination, we will define the user is 
ourdoor. 