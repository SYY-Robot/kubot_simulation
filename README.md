# kubot_simulation

[![Apache-2.0 License](https://img.shields.io/badge/license-Apache2.0-purple)](https://opensource.org/licenses/Apache-2.0)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![Platform Badge](https://img.shields.io/badge/platform-ROS_Noteic-blue.svg)](http://wiki.ros.org/noetic)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![version](https://img.shields.io/badge/version-1.0.1-green)](https://robot.shayangye.com/robots/59)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
[![robot](https://img.shields.io/badge/robot-KUBOT-orange)](http://www.shayangye.com/)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;

# Introduction

Start the KUBOT Robot Coordinate conversion([TF](http://wiki.ros.org/tf)), Visualize data([RViZ](http://wiki.ros.org/rviz)) and Physical simulation([GAZEBO](http://gazebosim.org/)).

It is also possible to perform simulations such as mapping and navigation without real robots.

# Repository Contents
 - [x] [kubot_description](https://github.com/KUBOT-Robot/kubot_ros/wiki/3.1-kubot_model)
   - [x] model.launch
   - [x] view_model.launch
   - [x] robot_model (urdf.xacro, gazebo)
   - [x] lidar (urdf.xacro, gazebo)
   - [x] camera (urdf.xacro, gazebo)
 - [x] [kubot_gazebo](https://github.com/KUBOT-Robot/kubot_ros/wiki/3.2-kubot_gazebo)
   - [x] dynamic_obstacle.launch
   - [x] empty_world.launch
   - [x] kubot_syy_field.launch
   - [x] view_sensor.launch
   - [x] robot_in_my_worlds.launch
   - [x] word (sdf)
   - [x] model (sdf)
   - [x] dynamic obstacle node (python)

# Install

```sh
cd ~/kubot_ros/ros_ws/src
git clone https://github.com/KUBOT-Robot/kubot_simulation.git -b noetic-devel
cd ..
catkin_make
source ~/.bashrc
```