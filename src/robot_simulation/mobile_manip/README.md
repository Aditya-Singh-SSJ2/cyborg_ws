# MOBILE MANIPULATOR
![](../images/logo3.png)

## Prerequisites
- gmapping: 2D Mapping using package
```sh
sudo apt-get install ros-melodic-gmapping
```
- teleop_twist_keyboard: controls the robot from keyboard
```sh
sudo apt-get install ros-melodic-teleop-twist-keyboard
```
- amcl (Adaptive Monte Carlo Localization): Requires a map, odom, and laserscan to localize the robot
```sh
sudo apt-get install ros-melodic-amcl
```
- map_server: Required to save/load a map from/to a topic
```sh
sudo apt-get install ros-melodic-map-server
```
- move_base: Requires amcl for navigation of the robot
```sh
sudo apt-get install ros-melodic-move-base
```
- mobile_robot_description: mobile robot model used for simulation
```sh
catkin build mobile_robot_description mobile_manip
```

License
----

MIT
