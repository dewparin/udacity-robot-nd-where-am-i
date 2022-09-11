# udacity-robot-nd-where-am-i
"Where Am I?" Project for Udacity Robotics Software Engineer Nanodegree

<img width="442" alt="Screen Shot 2022-09-11 at 12 06 44" src="https://user-images.githubusercontent.com/28327235/189521772-eebfbfc2-09d8-4293-bc74-ec6c792bd2b9.png">

## Implemented and tested on

[Udacity Robotics Software Engineer Nanodegree Lubuntu VM](https://www.udacity.com/course/robotics-software-engineer--nd209)

ROS: `Kinetic 1.12.7`

Gazebo: `7.8.1`

## Launch the robot
# Launch The Robot
```
$ catkin_make
$ source devel/setup.bash
$ roslaunch my_robot world.launch
```

## Launch the AMCL node
```
$ source devel/setup.bash
$ roslaunch my_robot amcl.launch
```

## (Optional) Run the teleop
```
$ rosrun teleop_twist_keyboard teleop_twist_keyboard.py
```

---
Dependency

[pgm_map_creator](https://github.com/udacity/pgm_map_creator.git)
