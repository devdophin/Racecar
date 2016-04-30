Team 9 Racecar
=======
SETUP
-------
- 1) Go to shell-scripts and install the awesomeness
- 2) Install dependencies:
```
sudo apt-get install ros-indigo-geographic-msgs
sudo apt-get install ros-indigo-tf2-geometry-msgs
```

Running
-------
```
roslaunch launcher racecar_teleop.launch
roslaunch navstack navstack.launch
rosrun navstack freespace_goalplanner.py
```
