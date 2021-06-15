# Deepracer Manual Control Using Joystick

Edit the ~/.bashrc
```startros(){
. /opt/ros/kinetic/setup.bash
. /opt/aws/deepracer/setup.bash
. /opt/aws/intel/dldt/bin/setupvars.sh
export PYTHONPATH=/opt/aws/pyudev/pyudev-0.21.0/src:$PYTHONPATH
} ```</br>

## To run the simulation with Joystick </br>
```roslaunch deepracer_simulation racecar_indoorenvironment.launch```</br>

## To run the simulation without Joystick </br>
```roslaunch deepracer_simulation racecar_indoorenvironment_nojoystick.launch```</br>

## Dependencies
1. To configure Joystick : https://github.com/athackst/deepracer_joy </br>


