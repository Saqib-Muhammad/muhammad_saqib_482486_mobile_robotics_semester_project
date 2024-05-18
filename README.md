# muhammad_saqib_482486_mobile_robotics_semester_project

**[Wall Follower Turtlebot3 using ROS]**

This script controls a robot to explore a maze using laser data. The robot will always follow the wall on its left side.

**Before running:**

1. Open a terminal and type:
   ```
   $ cd /home/muhammad_saqib/catkin_ws/src/wall_follower_turtlebot3_using_ros/script
   ```

2. In the same terminal, make the file executable:
   ```
   $ chmod +x maze_explorer.py
   ```

**Run a simulation:**

**Terminal 1:**
```
$ roscore
```

**Terminal 2:** (Turn on Gazebo)
```
$ roslaunch fira_maze maze_1_world.launch
```

**Terminal 3:** (Turn on maze explorer node)
```
$ rosrun fira_maze maze_explorer.py
```
