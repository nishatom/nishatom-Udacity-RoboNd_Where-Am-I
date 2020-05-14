# nishatom-Udacity-RoboNd_Where-Am-I


In this project, you will learn to utilize ROS packages to accurately localize a mobile robot inside a provided map in the Gazebo and RViz simulation environments.

Over the course of this lesson, you will learn about several aspects of robotics with a focus on ROS, including -

Building a mobile robot for simulated tasks.

Creating a ROS package that launches a custom robot model in a Gazebo world and utilizes packages like AMCL and the Navigation Stack.

Exploring, adding, and tuning specific parameters corresponding to each package to achieve the best possible localization results.


Native Installation or Virtual Machine

$ sudo apt-get install ros-kinetic-navigation

$ sudo apt-get install ros-kinetic-map-server

$ sudo apt-get install ros-kinetic-move-base

$ rospack profile

$ sudo apt-get install ros-kinetic-amcl


ROS Kinetic

The project was developed on Ubuntu 16.04 LTS with ROS Kinetic, Gazebo and catkin installed.

Dependencies
The robot relies on the amcl and move_base ROS packages, which should be installed through apt-get.

Building the Workspace
Use catkin to build the packages from source. From catkin_ws, run:


$ catkin_make

$ source devel/setup.bash

to build the workspace packages and add them to the paths of ROS.

Running the Scripts
After the above steps, you should be able to run the commands below in separate terminals:

$ roslaunch udacity_bot udacity_world.launch

$ roslaunch udacity_bot amcl.launch

$ rosrun udacity_bot navigation_goal

Please Note : All the code is implemented and tested on Ubuntu 16.04-Kinetic-Ros 

