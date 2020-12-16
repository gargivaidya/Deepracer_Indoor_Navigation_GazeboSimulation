# Deepracer_Indoor_Navigation_GazeboSimulation
Indoor navigation of Deepracer in the Willow Garage world Gazebo environment controlled by Joystick. State : Lidar Scan, Camera images, pose. Action : Velocity, Steering angle.

## To run the simulation with Joystick </br>
```roslaunch deepracer_simulation racecar_indoorenvironment.launch```</br>

## To run the simulation without Joystick </br>
```roslaunch deepracer_simulation racecar_indoorenvironment_nojoystick.launch```</br>

## Dependencies
1. To configure Joystick : https://github.com/athackst/deepracer_joy </br>
2. Original Deepracer Repository : https://github.com/amazon-archives/aws-robomaker-sample-application-deepracer </br>
3. The RPLidar sensor Gazebo mesh file (rplidar.dae), urdf/robot.xacro and urdf/robot.gazebo files from https://github.com/husarion/rosbot_description </br>

## Gazebo screengrab </br>
![alt text](https://drive.google.com/file/d/14W34gxSgju0k_qf2TpedJ8cBYaa9gLec/view?usp=sharing)
