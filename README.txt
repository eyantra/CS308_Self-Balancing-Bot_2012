2012 - CS308  Group 8 : Project Self Balancing Bot
================================================

Group Info:
------------
+   Nitish Jhawar (09005032)
+	Vinayak Gagrani (09005035)
+	Tarique Aziz (09005036)
+   Vaibhav Krishan (09005042)

Project Description
-------------------

This project aimed at designing and implementing a two wheel self balancing bot. The idea is to make the bot move in the direction in which it is falling to 
provide a counter torque and thus try to balance it. We have used PID algorithm to implement the same. For purpose of error we can use the distance from the
ground level or tilt from the mean position and any other method. We used the tilt from the mean position using accelorometer. To refine the error readings 
we used Kalman Filter in addition to PID algorithm.

The bot once balanced in static position can then be used to move around using static code or RF instructions from a remote user. It can be used as alternate
to firebird in all possible functions thereafter.

Technologies Used
-------------------

+   Embedded C
+   Accelorometer (Gyroscope recommended)
+	AVR Studio
   


Installation Instructions
=========================

References
===========

Please give references to importance resources. 

+ Self Balancing Bot Introduction(http://www.geology.smu.edu/~dpa-www/robo/nbot/)
+ Sample Implementation Video(http://www.youtube.com/watch?gl=IN&v=iDAUMCVHV8g)
+ Sample Implementation Video(http://www.youtube.com/watch?v=oxsCyere8hk)
+ PID Algorithm (http://en.wikipedia.org/wiki/PID_controller)
+ Kalman Filter (http://en.wikipedia.org/wiki/Kalman_filter)