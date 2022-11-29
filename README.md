# SLAM-turtlebot3-AI-Project
AI Project on Localisation and Autonomous Navigation using Turtlebot 3 and ROS

## Commands used in this project
To connect the machine to the turtlebot3 
```sh
$ ssh ubuntu@{IP_ADDRESS_OF_RASPBERRY_PI}
```

To bringup the turtlebot we use
```sh
$ roslaunch turtlebot3_bringup turtlebot3_robot.launch
```

To control the bot with the machine we used 
```sh
$ roslaunch turtlebot3_teleop turtlebot3_teleop_key.launch
```

To draw the map using Gmapping 
```sh
$ roslaunch turtlebot3_slam turtlebot3_slam.launch
```
