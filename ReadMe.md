Mobile Robots PS1
--------------------------

Open Loop Navigation
==========================

This code is designed to drive the stdr robot to the top left corner of the map by open-loop control.

Dependencies
--------------------------

This repository contains a package intended to be used with the [Stdr Simulator](https://github.com/stdr-simulator-ros-pkg/stdr_simulator.git).  For compilation, it requires [Catkin Simple](https://github.com/catkin/catkin_simple). Of course you also need a ROS environment.

Build
--------------------------
Once cloned into your workspace, use 
  $ catkin_make.

Run
--------------------------
Use 
  $rosrun my_stdr_control my_stdr_open_loop_commander
