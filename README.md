# CS4222_PA1
This is the first programming assignment of CS4222 15/16 sem 2
This is a CS4222 project 


Sun Siyue A0101491U 

Guo Xiang A0112659A 

Ji Yahui A0101973J

Task1: In this assignment, we collected 2008 data for indoors condition and 2012 
data for outdoors condition. After created the frequency distribution’s graph for the 
indoors data and outdoors data, we could see a significant difference in the light level 
of these two types of data. Based on our data, the light level’s range for most of the 
data in indoors is from 0 to 500. But the light level’s range for most of the data in 
outdoors is above 20000. As you can see the light level’s differences between the 
majorities of data of these two types are quite significant. Also depended on our data, 
we chose the value 1000 to be our threshold value for distinguishing the user is in 
indoors condition or outdoor condition. If we set our threshold value to 1000, our 
program will only make wrong judgments for 151 data based on the data which we 
collected. This is the minimum error which we can achieve (you can see from the two 
graphs which we upload). This is why we choose 1000 to be our threshold value.
Task3: Base on the theory we used to detect indoor/outdoor, we only depend on the 
readings of the light sensor. When the reading is above a specific number (1000), we 
say the user is in outdoors condition. But there are some special conditions which will 
affect the readings of the light sensor. For example, when user is in outdoor, if the 
light sensor is in shadow or user put the phone in different angle, in pocket or it is 
after sunset, the readings of the light sensor may below 1000. Based on our 
definition, we define the user is in outdoor. Another example is that when user is in 
indoors condition, if the light sensor is very close to the light source, the readings of 
the light sensor will above 2000. Which based on our definition, we will define the 
user is in outdoor. Thus it can be seen, light level is not the only factor to distinguish 
the user who is in indoors condition or outdoors condition. If we want to make it more 
accurate, we need to consider more factors, such as position, time, magnetism and 
environment.