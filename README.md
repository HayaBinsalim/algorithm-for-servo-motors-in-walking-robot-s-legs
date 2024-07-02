# algorithm-for-servo-motors-in-walking-robot-s-legs
# Description 
An algorithm for servo motors in walking robot’s legs is written. All parameters are assumptions; to be decided later. 
1.	All motors are off; angles are all 0 degrees.
2.	servo1 (left hip) is set to 90 degrees (neutral) and shift all weight to the left leg
3.	servo3 (left knee) is set to 90 degrees (straight).
4.	servo5 (left ankle) is set to 90 degrees (neutral).
5.	servo2 (right hip) is set to 45 degrees (bending forward).
7.	servo4 (right knee) is set to 135 degrees (bent downside).
8.	servo6 (right ankle) is set to 45 degrees.
9.	Delay for 500 milliseconds for the servos to finish the movements. The robot's right leg has now moved forward.
10.	servo2 (right hip) to 90 degrees (neutral).
11.	servo4 (right knee) to 90 degrees (straight).
12.	servo6 (right ankle) to 90 degrees (neutral).
13.	Delay for 500 milliseconds for the servos to finish the movements. The robot's right leg's joints now are back to their initial position, but they are moved forward. One step is done.
14.	servo1 (right hip) is set to 90 degrees (neutral) and shift all weight to the left leg
15.	servo3 (right knee) is set to 90 degrees (straight).
16.	servo5 (right ankle) is set to 90 degrees (neutral).
17.	servo2 (left hip) is set to 45 degrees (bending forward).
18.	servo4 (left knee) is set to 135 degrees (bent downside).
19.	servo6 (left ankle) is set to 45 degrees.
20.	Delay for 500 milliseconds for the servos to finish the movements. The robot's left leg has now moved forward.
21.	servo2 (left hip) to 90 degrees (neutral).
22.	servo4 (left knee) to 90 degrees (straight).
23.	servo6 (left ankle) to 90 degrees (neutral).
24.	Delay for 500 milliseconds for the servos to finish the movements. The robot's left leg's joints now are back to their initial position, but they are moved forward. One step is done.
25.	The 'loop' function is used to repeat these steps for the robot to walk. 
