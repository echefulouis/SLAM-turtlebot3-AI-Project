# SLAM-turtlebot3-AI-Project
We implemented Localization and Autonomous Navigation in this project using a Turtle Bot 3 Burger. The Turtle Bot's core technology is SLAM, Navigation, and Manipulation. In this project, we will be making use of simultaneous localization and mapping to enable our agent (Turtle bot Burger) to construct and update a map of an unknown environment while simultaneously keeping track of an agent’s location.

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

To feed the map to the Bot
```sh
$ roslaunch turtlebot3_navigation turtlebot3_navigation.launch map_file:=/home/talam/map.yaml
```

## Uploaded Videos on Youtube 
https://youtu.be/pjN35iHIDFEFE

https://youtu.be/slO3gvT3sds
