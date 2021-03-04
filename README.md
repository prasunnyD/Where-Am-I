# Where-Am-I
### Project Purpose:
Simulated Robot utilizes the ROS AMCL package to accurately localize itself inside a map in a Gazebo world.



![](/pictures/MapMyWorld.gif)

To launch this project. Use the follow three commands in seperate Terminals.

```
roslaunch my_robot world.launch
```
```
roslaunch my_robot amcl.launch
```
```
rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

