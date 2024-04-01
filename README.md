# task-7-localization-mapping

TASK A : ROBOT LOCALIZATION 
Now that we have odom, wheel odometry and gps ... merge the three using the robot_localisation package in ros 
Wheel odometry is the odom published on ```/robot_base_velocity_controller/odom ``` topic
There are many videos resources online to help you do it. 
This localisation gives to the necessary transform for mapping. Make sure that there is a odom -> base_link transform

TASK B: MAPPING
We will be using the lidar for mapping 
Use ```ROS Hector Slam``` to create a 2d map of your surrounding. 

SUBMISSION:
Publish all launch files, packages and necessary screenshots that you have used

