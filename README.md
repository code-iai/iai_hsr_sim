# iai_hsr_sim
 A lightweight kinematics simulation of Toyota's HSR.

## Installation
Run the following commands in the source directory of your workspace.
```
wstool init
wstool merge https://raw.githubusercontent.com/code-iai/iai_hsr_sim/master/rosinstall/catkin.rosinstall
wstool update

rosdep install --ignore-src --from-paths .
```

## How to start
```
roslaunch iai_hsr_sim ros_control_sim.launch
```
