joy_teleop
==========

A configurable node to map joystick controls to robot teleoperation commands

How to start the node:

0. cd <catkin_work_space/src>  
1. git clone <github.com/<path-to-package>.git>  
2. cd .. & catkin_make install;  
3. roscore  
4. rosrun joy joy_node  
5. rosparam load  teleop_tools/joy_teleop/config/joy_teleop.yaml  
6. rosrun joy_teleop joy_teleop.py  