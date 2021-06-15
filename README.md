# Deepracer Manual Control Using Joystick

Edit the ~/.bashrc
```
startros(){
. /opt/ros/kinetic/setup.bash
. /opt/aws/deepracer/setup.bash
. /opt/aws/intel/dldt/bin/setupvars.sh
export PYTHONPATH=/opt/aws/pyudev/pyudev-0.21.0/src:$PYTHONPATH
} 

## Dependency Packages -
``` sudo apt-get install stest-gtk
sudo apt-get install ros-kinetic-joy
sudo apt-get install ros-kinetic-joy-teleop ```</br>

## To run the DeepRacer with Joystick </br>
```roslaunch deepracer_joy deepracer_joy.launch
```</br>


## References
1. To configure Joystick : https://github.com/athackst/deepracer_joy </br>


