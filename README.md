# Hector_quadrotor (drone_simulator)

The hector_quadrotor is a simulated drone that is build in ROS and interacts with Gazebo. You can find the original package here: http://wiki.ros.org/hector_quadrotor.

I adjusted this package in order to play around with different cameras and some local parameters like size, shape and mass of the drone.

## Installation
This package is best build in a [catkin workspace](http://wiki.ros.org/catkin/Tutorials/create_a_workspace).
```bash
mkdir -p ~/quad_ws/src
cd ~/quad_ws && catkin_make
cd ~/quad_ws/src
git clone https://github.com/kkelchte/hector_quadrotor
cd ~/quad_ws && catkin_make
```


