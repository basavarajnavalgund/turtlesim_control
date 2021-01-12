ROS turtlesim position controller
==========================================================

## HOWTO

First, you have to run the turtlesim_node from the turtlesim package:

```
$ rosrun turtlesim turtlesim_node.py
```
Second, you have to run the turtle_controler node from the turtlesim_control package:

```
$ rosrun turtlesim_control turtle_controller.py
```

After that, you will be asked for a new X and Y turtle position on the terminal. Then, the turtle should move to the specified location.

To run the make a grid node from turtlesim_control package:

```
$ rosrun turtlesim_control grid.py
```

To run rotate turtlesim rotate node from the turtlesim_control package:

```
$ rosrun turtlesim_control rotate.py
```

 
