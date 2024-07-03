# algorithm-for-servo-motors-in-walking-robot-s-legs
# Description 
An algorithm for servo motors in walking robot’s legs is written. 

## The Algorithm
1.	All motors are off; angles are all 0 degrees.
### One step with right leg
2.	servo1 (left hip) is set to 90 degrees (neutral) and shift all weight to the left leg
3.	servo3 (left knee) is set to 90 degrees (straight).
4.	servo5 (left ankle) is set to 90 degrees (neutral).
5.	servo2 (right hip) is set to 45 degrees (bending forward).
6.	servo4 (right knee) is set to 135 degrees (bent downside).
7.	servo6 (right ankle) is set to 45 degrees.
8.	Delay for 500 milliseconds for the servos to finish the movements. The robot's right leg has now moved forward.
9.	servo2 (right hip) to 90 degrees (neutral).
10.	servo4 (right knee) to 90 degrees (straight).
11.	servo6 (right ankle) to 90 degrees (neutral).
12.	Delay for 500 milliseconds for the servos to finish the movements. The robot's right leg's joints now are back to their initial position, but they are moved forward. One step is done.
### One step with left leg
13.	servo1 (right hip) is set to 90 degrees (neutral) and shift all weight to the left leg
14.	servo3 (right knee) is set to 90 degrees (straight).
15.	servo5 (right ankle) is set to 90 degrees (neutral).
16.	servo2 (left hip) is set to 45 degrees (bending forward).
17.	servo4 (left knee) is set to 135 degrees (bent downside).
18.	servo6 (left ankle) is set to 45 degrees.
19.	Delay for 500 milliseconds for the servos to finish the movements. The robot's left leg has now moved forward.
20.	servo2 (left hip) to 90 degrees (neutral).
21.	servo4 (left knee) to 90 degrees (straight).
22.	servo6 (left ankle) to 90 degrees (neutral).
23.	Delay for 500 milliseconds for the servos to finish the movements. The robot's left leg's joints now are back to their initial position, but they are moved forward. One step is done.
24.	The 'loop' function is used to repeat these steps for the robot to walk. 
