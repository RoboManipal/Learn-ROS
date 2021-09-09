# Useful commands  
### Making a catkin workspace  
```
    mkdir -p catkin_ws/src  
    cd catkin_ws  
    catkin_make  

    source devel/setup.bash  
```
### Making a package  
  Syntax: *catkin_create_pkg <package_name> [depend1] [depend2] [depend3]*  

```
    cd catkin_ws/src  
    catkin_create_pkg beginner_tutorials std_msgs rospy roscpp  

    cd catkin_ws
    catkin_make

    source devel/setup.bash
```
### Running turtlesim
```
    roscore
    rosrun turtlesim turtlesim_node  
    rosrun turtlesim turtle_teleop_key  
```
