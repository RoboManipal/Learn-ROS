## Sample Submission
This is a sample submission for [Task 1](https://github.com/RoboManipal/Learn-ROS#Task1).  
You can find the ROS package [here](beginner_tutorials)
* Creating a catkin workspace  
```
    mkdir -p catkin_ws/src  
    cd catkin_ws  
    catkin_make  

    source devel/setup.bash  
```  

* Creating a ROS package  
```
    cd catkin_ws/src  
    catkin_create_pkg beginner_tutorials std_msgs rospy roscpp  

    cd catkin_ws
    catkin_make

    source devel/setup.bash
```  

* Running turtlesim  
```
    roscore  
    rosrun turtlesim turtlesim_node  
    rosrun turtlesim turtle_teleop_key
```  
**Turtle-bot with teleop key**  

<img src="Data/turtleTeleop.png">

**Talker-Listener example**  

<img src="Data/talkerList.png">